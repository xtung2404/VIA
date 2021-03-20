# Cài đặt môi trường giả lập . 
## Dowload các file cần thiết .
Hiện nay , Maker Hà Nội đã tạo ra được chương trình giả lập xe  trên 3 hệ điều hành khác nhau : Linux , Windows , MacOS.
Tùy theo từng hệ điều hành các bạn sử dụng , các bạn có thể dowload theo [link này .](https://github.com/makerhanoi/via-simulation-jeep/releases/tag/v0.1-alpha "Github Maker Hanoi")
![](https://i.imgur.com/Usr2cTl.png).

Nếu bạn sử dụng hệ điều hành : 
* Windows -> Select : via-simulation-windows-x86_64-20210314.zip
* Linux -> Select : via-simulation-linux-x86_64-20210314.zip
* MacOS -> Select : via-simulation-macos-x86_64-20210314.zip. 


Các bạn dowload các file zip về và giải nén file . 

## Cài đặt source code
### Đầu tiên , các bạn [vào link này](https://github.com/makerhanoi/hello-via)
![](https://i.imgur.com/Usr2cTl.png)
### ->Select **Code** 
![](https://i.imgur.com/TUG9FiX.png)
### -> **Dowload ZIP**
![](blob:https://imgur.com/69c55389-6694-4cff-a48f-084c1b7f20ab)
Các bạn dowload file về và giải nén 

## Cài đặt miniconda 3
###Để có thể khởi động được xe , bạn cần cài đặt phần mềm [Miniconda 3](https://docs.conda.io/en/latest/miniconda.html)
Có các lựa chọn khác nhau , bạn dowload theo hệ điều hành mình sử dụng , như mình sẽ chọn **Windows Installers -> Python 3.8 -> Miniconda 3 Windows 64-bit**
Trong lúc cài đặt các bạn nhớ 1 số lưu ý sau : 
![](https://i.imgur.com/aSkRwc7.png)
![](https://i.imgur.com/VpDTeSq.png)

## Cài đặt môi trường 


1. Chúng mình sẽ sử dụng **Visual Studio Code** nên các bạn nhớ dowload trước về nhé .
2. Open **File -> Open File -> hello-via-master**
3. Cài đặt môi trường giả lập miniconda : **conda create -n <Tên môi trường> python=3.7** -> y -> Enter
4. Nhập lệnh **conda activate <Tên môi trường>** để khởi động môi trường
5. Cài những gói cần thiết : **pip install -r requirements.txt**
