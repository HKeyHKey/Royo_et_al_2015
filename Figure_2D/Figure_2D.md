Statistical test in R:

``data=read.csv('Spo11KO_threeIndividuals.csv',header=T);shapiro.test(data$FC.61.283i[data$Type=='Autosomal miR']);shapiro.test(log(data$FC.61.283i[data$Type=='Autosomal miR']));wilcox.test(c(data$FC.61.283i[data$Type=='Autosomal miR'],data$FC.62.289i[data$Type=='Autosomal miR'],data$FC.62.289k[data$Type=='Autosomal miR']),c(data$FC.61.283i[data$Type=='X miR'],data$FC.62.289i[data$Type=='X miR'],data$FC.62.289k[data$Type=='X miR']))``
