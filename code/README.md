# Code

Save command-line scripts and shared R code here.
x <- seq(0.2, 1, 0.2)
x2 <- x[c(3, 5)]
x3 <- x[c(-2, -4)]
x[1] <- 0
video = c(47, 63, 58, 53, 53, 63, 53, 39, 58, 50)
video5 <- video[video < 52]
video6 <- video[video <= 53]
mean7 <- mean(video) > 50
videoSectionB = c(47, 57, 47, 50, 55, 69, 26, 33, 56)
allVideo = c(video,videoSectionB)
totalStudent8 <- sum(allVideo > 58)
Variance9 <- var(allVideo < 53)
flavor10 = c("C","V", "S", "S", "V", "V", "V", "V", "V", "V", "V",
"V", "S", "V", "V", "V", "S", "C", "V")
NumFlavor10 <- factor(c("C","V", "S", "S", "V", "V", "V", "V", "V", "V", "V",
"V", "S", "V", "V", "V", "S", "C", "V"))
ValuesIceCream <- summary(NumFlavor10)
PropStrawberry <- (3/19)
