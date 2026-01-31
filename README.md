r
## (K-5) MLE objective function
fitFun <- function(x, fX, fy, optimizeP, useLambda, penval) {
  krigingLikelihood(x, fX, fy, optimizeP, useLambda, penval)$NegLnLike
}
