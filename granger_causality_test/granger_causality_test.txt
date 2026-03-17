# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Perform a Granger Causality Test on Two Time Series Use granger_causality_test (grangersearch) With (In) R Software
install.packages("grangersearch")
library("grangersearch")
# Estimation Perform a Granger Causality Test on Two Time Series Use granger_causality_test (grangersearch) With (In) R Software
granger_causality_test = read.csv("https://raw.githubusercontent.com/timbulwidodostp/granger_causality_test/main/granger_causality_test/granger_causality_test.csv",sep = ";")
x <- granger_causality_test$Independen
y <- granger_causality_test$Dependen
granger_causality_test <- granger_causality_test(x = x, y = y)
summary(granger_causality_test)
# Perform a Granger Causality Test on Two Time Series Use granger_causality_test (grangersearch) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
