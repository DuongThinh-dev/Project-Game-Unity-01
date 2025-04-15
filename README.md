# 🎮 Project Game Unity 01

Một dự án game được phát triển bằng Unity nhằm rèn luyện kỹ năng lập trình game, thiết kế gameplay và xử lý các tương tác cơ bản.

## 🚀 Giới thiệu

Dự án này bao gồm:

- Hệ thống điều khiển nhân vật theo kiểu lưới (grid-based movement)
- Cơ chế nhảy, thu thập vật phẩm (coin), và tương tác với chướng ngại vật
- Kẻ địch sử dụng `NavMeshAgent` để truy đuổi người chơi
- Các hiệu ứng hoạt hình (animation), âm thanh và tương tác vật lý
- Reset vị trí khi va chạm với hazard hoặc kẻ địch

## 🛠 Công nghệ sử dụng

- **Unity** (version XYZ)
- **C#**
- **NavMesh** cho AI pathfinding
- **Animator**, **Rigidbody**, và **Collider** cho gameplay

## 🎯 Mục tiêu

- Hiểu và thực hành xây dựng một hệ thống gameplay cơ bản
- Làm quen với cách sử dụng Unity hiệu quả hơn
- Tạo nền tảng cho các dự án game phức tạp hơn trong tương lai

## 📂 Cấu trúc thư mục

```plaintext
Assets/
├── Scripts/              # Các script C#
├── Prefabs/              # Các prefab đã tạo sẵn
├── Scenes/               # Các màn chơi
├── Audio/                # Âm thanh
└── Art/                  # Hình ảnh, sprite, model 3D (nếu có)
