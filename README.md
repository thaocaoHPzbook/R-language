# 1. Cách đọc dữ liệu vào R
## 1.1. Đọc dữ liệu từ excel
B1: Cài đặt package    
    `install.packages("gdata")`   
#R sẽ bắt chọn gói ngôn ngữ, nên chọn gói US/Vietnamese   
B2:
**Gọi gói gdata trước khi sử dụng**    
library("gdata")    
**Nếu là xls files**    
my_data <- read_excel("my_file.xls")    
hoặc my_data = read_excel("my_file.xls", header=T) 
**Nếu là xlsx files**    
my_data <- read_excel("my_file.xlsx")    
hoặc my_data = read_excel("my_file.xlsx", header=T)    

