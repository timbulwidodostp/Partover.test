# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# The partially overlapping samples t-test Use Partover.test (Partiallyoverlapping) With (In) R Software
install.packages("Partiallyoverlapping")
library("Partiallyoverlapping")
Partover.test = read.csv("https://raw.githubusercontent.com/timbulwidodostp/Partover.test/main/Partover.test/Partover.test.csv",sep = ";")
# Estimation The partially overlapping samples t-test Use Partover.test (Partiallyoverlapping) With (In) R Software
Partover.test_1 <- Partover.test$Partover.test_1
Partover.test_2 <- Partover.test$Partover.test_2
Partover.test_3 <- Partover.test$Partover.test_3
Partover.test_4 <- Partover.test$Partover.test_4
Partover.test(Partover.test_1, Partover.test_2, Partover.test_3, Partover.test_4, var.equal = TRUE) 
Partover.test(Partover.test_1, Partover.test_2, var.equal = TRUE, stacked = TRUE)
# The partially overlapping samples t-test Use Partover.test (Partiallyoverlapping) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished