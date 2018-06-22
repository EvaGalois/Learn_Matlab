# Learn_Matlab

# Matlab数据结构
- 数字
- 字符与字符串
- 矩阵
- 元胞数组
- 结构体

clear all
clc
A = rand(3,5)
rows = size(A,1)
cols = size(A,2)

s = 'a'
abs(s)
char(65)
num2str(65)
str = 'I Love MATLAB & Machine Learning.'
lenth(str)
doc num2str
A = [1 2 3; 4 5 2; 3 2 7]
B = A'
E = zeros(10,5,3)
E(:,:,1) = rand(10,5)
E(:,:,2) = randi(5, 10,5)
E(:,:,3) = randn(10,5)
A = cell(1, 6)
A{2} = eye(3)
A{5} = magic(5)
B = A{5}
books = struct('name',{{'Machine Learning','Data Mining'}},'price',[30 40])
books.name
books.name(1)
books.name{1}
A = [1 2 3 5 8 5 4 6]
B = 1:2:9
C = repmat(B, 3, 1)
D = ones(2, 4)

