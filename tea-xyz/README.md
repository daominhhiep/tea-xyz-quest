- Cài đặt nodejs và npm tại https://nodejs.org/en

- Tải file và lưu ở desktop

- Truy cập github.com tạo repository với tên tea-xyz-quest (Phải để repo public)

- Truy cập https://www.npmjs.com để tạo tài khoản

- Sửa file package.json, theo format
  - name => @username_npm/tea-xyz-quest 
  - author => @username_npm
  - repository => link tới repo github vừa tạo

- Truy cập repo github vừa tạo và upload cả folder vừa sửa lên https://github.com/daominhhiep/tea-xyz-quest/upload

- Mở terminal, gõ lệnh "npm -v" để kiểm tra xem đã cài đặt thành công npm ở bước 1 chưa

- Gõ tiếp lệnh "cd Desktop/tea-xyz-quest" để trỏ tới thư mục code 

- "npm login" => Có 1 đường dẫn để bấm vào sẽ mở trình duyệt dẫn tới web login npm

- Sau khi login thành công gõ lệnh "npm publish --access public" để public package lên npm publish. Truy cập npm để check VD: https://www.npmjs.com/package/@daominhhiep/tea-xyz-quest

- Truy cập app.tea.xyz => Register a New OSS Project

- Tìm kiếm tên package vừa tạo. VD: @daominhhiep/tea-xyz-quest . Bước này có thể mất tới 2-3 ngày để package mới xuất hiện trên hệ thống của tea.xyz

- Sau đó tea sẽ cho 1 file có tên tea.yaml, tải về và quay lại repo github, upload tiếp file đó lên là xong 