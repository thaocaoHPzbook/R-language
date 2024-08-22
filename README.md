# 1. Cách đọc dữ liệu excel vào R
## 1.1. Đọc trực tiếp
B1: Cài đặt package gdata    
    `install.packages("gdata")`   
#R sẽ bắt chọn gói ngôn ngữ, nên chọn gói US/Vietnamese   
B2: nói cho R biết chúng ta làm việc ở folder nào bằng lệnh setwd    
`setwd("/kéo đường dẫn")`    
B3:
**Gọi gói gdata trước khi sử dụng**    
`library("gdata")`    
B4: lệnh đọc file
**Nếu là xls files**    
`fto <- read.xls("FTO gene.xls")`    
`hoặc fto = read.xls("FTO gene.xls", header=T)`   
**Nếu là xlsx files**    
`fto <- read.xlsx("FTO gene.xls")`    
`hoặc fto = read.xlsx("FTO gene.xls", header=T)`    

