# SPCK

## Các phần cần có ở trong sản phẩm

- [ ] Có phần đăng nhập/đăng ký sử dụng localStorage
  - [ ] Lưu được nhiều tài khoản
  - [ ] Có thể nâng cấp lên dùng Firebase
- [ ] Lấy dữ liệu từ API
  - [ ] Tìm trên mạng (jsonplaceholder, rapidapi, ...)
  - [ ] Có thể nâng cấp lên dùng Firebase Realtime Database, Firestore
- [ ] Render trang HTML bằng JS và dữ liệu lấy từ API
- [ ] Tham khảo các thư viện UI (PinesUI, Flowbite, DaisyUI, ...)
- [ ] Responsive (trên màn hình mobile và desktop)

## Git

### Làm lần đầu tiên

Tạo một repo trên Github và clone về máy

```bash
git clone https://github.com/code-tieumomo/JSA10.git
```

### Làm mỗi khi code

- Vào tab `Source Control` của VSCode (Ctrl + Shift + G)
- Bấm vào nút `...` bên cạnh chữ `SOURCE CONTROL` và chọn `Pull` để lấy code mới về
- Có một số mục cần lưu ý:
  - Changes: Danh sách các file đã thay đổi/thêm mới/xóa đi
    - Bấm vào từng file để xem sự thay đổi là gì
    - Bấm vào dấu "+" để thêm file vào Staged Changes
  - Staged Changes: Danh sách các file đã được đánh dấu để sẵn sàng commit
    - Bấm vào dấu "-" để bỏ file ra khỏi Staged Changes
- Để commit, điền vào mục `Message` và bấm nút `✓ Commit` bên dưới
- Để push lên Github, bấm vào nút `...` bên cạnh chữ `SOURCE CONTROL` và chọn `Push`

### Các thư viện hỗ trợ

- UI:
  - Pines UI:
    - How to use: <https://devdojo.com/pines/docs/how-to-use>

    ```html
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Pines UI</title>
        <style>
          [x-cloak] {
            display: none;
          }
        </style>
        <!-- Include the Alpine library on your page -->
        <script src="https://unpkg.com/alpinejs" defer></script>
        <!-- Include the TailwindCSS library on your page -->
        <script src="https://cdn.tailwindcss.com"></script>
      </head>
      <body class="flex items-start justify-center h-full bg-gray-50">
        <div class="flex items-center justify-center w-full max-w-full">
          <!-- Element Here -->
        </div>
      </body>
    </html>
    ```

    - Components: <https://devdojo.com/pines/marketing/blog>

  - Flowbite
    - How to use:

    ```html
    <link href="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.8.0/flowbite.min.css"  rel="stylesheet" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.8.0/flowbite.min.js"></script>
    ```

    - Components: <https://flowbite.com/docs/components/accordion/>
    - Blocks: <https://flowbite.com/blocks/>
  - DaisyUI:
    - How to use:

    ```html
    <link href="https://cdn.jsdelivr.net/npm/daisyui@3.5.1/dist/full.css" rel="stylesheet" type="text/css" />
    <script src="https://cdn.tailwindcss.com"></script>
    ```

    - Components: <https://daisyui.com/components/accordion/>

  - Một số thư viện khác yêu cầu TailwindCSS
    - TailwindUI:
      - How to use:

      ```html
      <script src="https://cdn.tailwindcss.com"></script>
      ```

      - Components: <https://tailwindui.com/components>
    - HyperUI: <https://www.hyperui.dev/>
    - Meraki: <https://merakiui.com/components>
    - Myna UI: <https://mynaui.com/>
    - Tailblock: <https://tailblocks.cc/>
    - Tailwind UI Kit: <https://tailwinduikit.com/components>
    - <https://www.tailwindawesome.com/?price=free>

- Icons:
  - Static: <https://icones.js.org/>
  - Animated: <https://lordicon.com/icons>

- Data:
  - API:
    - <https://rapidapi.com/>
    - <https://jsonplaceholder.typicode.com/>
  - localStorage:
    - <https://raw.githubusercontent.com/nbubna/store/master/dist/store2.min.js>

      ```html
      <script src="https://raw.githubusercontent.com/nbubna/store/master/dist/store2.min.js" type="text/javascript"></script>
      ```

- JS:
  - AlpineJS: <https://alpinejs.dev/>
  - Jquery: <https://jquery.com/>
  - ChartJS: <https://www.chartjs.org/>
  - Isotope: <https://isotope.metafizzy.co/>

## Topic

- Portfolio: <https://forst.qodeinteractive.com/>
  - Trang chủ: show danh sách các dự án đã từng làm
  - Chi tiết: thông tin chi tiết + hình ảnh về 1 dự án
  - Trang thông tin cá nhân
  - Trang liên hệ
  - Trang pricing
  - Trang danh sách blog
  - Trang chi tiết blog

- LMS: <http://themeturn.com/tf-db/eduhash/theme/course-grid.html>
  - Trang danh sách khóa học
  - Trang chi tiết khóa học
  - Trang chi tiết một buổi học
  - Trang giới thiệu
  - Trang liên hệ
  - Trang pricing

- Trang tin tức
- Trang bán hàng

- Hệ thống quản lý bán hàng/nhân sự/...
  - Trang danh sách
  - Trang chi tiết
  - Trang chỉnh sửa
  - ...
