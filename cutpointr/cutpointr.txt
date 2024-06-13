# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Determine and Evaluate Optimal Cutpoints in Binary Classification Tasks Use cutpointr With (In) R Software
install.packages("cutpointr")
library("cutpointr")
cutpointr = read.csv("https://raw.githubusercontent.com/timbulwidodostp/cutpointr/main/cutpointr/cutpointr.csv",sep = ";")
# Estimation Determine and Evaluate Optimal Cutpoints in Binary Classification Tasks Use cutpointr With (In) R Software
cutpointr <- cutpointr(cutpointr, rating, disease, method = maximize_metric, metric = sum_sens_spec)
summary(cutpointr)
plot(cutpointr)
# Determine and Evaluate Optimal Cutpoints in Binary Classification Tasks Use cutpointr With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished