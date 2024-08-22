# 1. Cách đọc dữ liệu vào R
## 1.1. Đọc dữ liệu từ excel
B1: Cài đặt package    
    `install.packages("readxl")`   
#R sẽ bắt chọn gói ngôn ngữ, nên chọn gói US (tiếng anh)
B2:
# Loading
library("readxl")
# Nếu là xls files
my_data <- read_excel("my_file.xls")
#  Nếu là xlsx files
my_data <- read_excel("my_file.xlsx")

