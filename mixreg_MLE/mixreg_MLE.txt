# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# MLE (Maximum Likelihood Estimation) of Mixture Regression with Normal Errors Use mixreg (MixSemiRob) With (In) R Software
install.packages("MixSemiRob")
library("MixSemiRob")
# Estimation MLE (Maximum Likelihood Estimation) of Mixture Regression with Normal Errors Use mixreg (MixSemiRob) With (In) R Software
mixreg_MLE = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mixreg_MLE/main/mixreg_MLE/mixreg_MLE.csv",sep = ";")
mixreg_1 = mixreg(mixreg_MLE$mixreg, mixreg_MLE$mixreg_1)
mixreg_2 = mixreg(mixreg_MLE$mixreg, mixreg_MLE$mixreg_2)
mixreg_3 = mixreg(mixreg_MLE$mixreg, mixreg_MLE$mixreg_3)
mixreg_1
mixreg_2
mixreg_3
# MLE (Maximum Likelihood Estimation) of Mixture Regression with Normal Errors Use mixreg (MixSemiRob) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished