# DATDEV INSTALLER

Cài phần mềm tự động

## Chức năng bản v1
- Cài Google Chrome
- Cài WinRAR
- Cài UniKey
- Cài Brave
- Cài Microsoft Office 365
- Cài nhiều phần mềm cùng lúc
---
## Cách sử dụng


1. Tải file `install.exe`
2. Chuột phải
3. Chọn `Run as administrator`
4. Chọn phần mềm muốn cài
<img width="630" height="536" alt="image" src="https://github.com/user-attachments/assets/e051dcbf-01fc-423a-a3a9-c1a2a6af25da" />
 
---
# Cài đặt winget

Nếu mở file .exe mà bị lỗi dạng gần giống như thế này
<img width="917" height="235" alt="image" src="https://github.com/user-attachments/assets/596031d9-2911-4a52-9427-5106fb924651" />
`powershell winget is not recognized`

##Chi tiết khắc phục 
 
 (Có thể vào Microsoft Store tìm từ khóa tên winget rồi install còn không tải từ github về)
1. Tải file tên  `Microsoft.DesktopAppInstaller_8wekyb3d8bbwe.msixbundle` từ [Github bản Winget v1.28.240](https://github.com/microsoft/winget-cli/releases/tag/v1.28.240)
2. Double click file chọn install
3. Mở Windows PowerShell nhập `winget` nếu thấy hiện help menu là ok.
