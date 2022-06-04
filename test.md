首先下载LSB-Steganography，修改LSBSteg.py
通过python3 LSBSteg.py encode -i input.png -o test.png -f info.txt进行加密，将ID和姓名隐藏在图像的颜色中
通过python3 LSBSteg.py decode -i test.png -o info2.txt即可提取出隐藏在图像中的信息
