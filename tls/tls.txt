# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fitting error-in-variables models via total least squares Use tls With (In) R Software
install.packages("tls")
library("tls")
tls = read.csv("https://raw.githubusercontent.com/timbulwidodostp/tls/main/tls/tls.csv",sep = ";")
# Estimation Fitting error-in-variables models via total least squares Use tls With (In) R Software
tls <- tls(Y ~ X.1 + X.2 - 1, data = tls)
tls
# Fitting error-in-variables models via total least squares Use tls With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished