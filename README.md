# assignment8.R
library(MASS)
dat<-data(ships)

disprove <- plot(ships$type, ships$service)
disprove
## as the aggregate months of service of ship B is more ...it disaprove the statement of ship b is less trust worthy
