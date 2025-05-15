# PortaLocal - Create Localhost Quickly

**English** | [Tiếng Việt](#portalocal---tạo-localhost-nhanh-chóng)

## About
PortaLocal is a user-friendly GUI tool developed by Truong Quoc Nam (Trương Quốc Nam) to create and manage local HTTP/HTTPS servers. Built with Python and Tkinter, it allows users to select a directory, specify a port, choose between HTTP or HTTPS, and start/stop a server effortlessly. It supports self-signed SSL certificates for HTTPS and includes a built-in terminal for server logs. PortaLocal is open-source under the [GNU General Public License v3.0](LICENSE).

## Features
- Start and stop HTTP/HTTPS servers via an intuitive GUI.
- Browse or manually enter directories to serve content.
- Support for HTTP and HTTPS with automatic self-signed certificate generation.
- Customizable port selection with history tracking.
- Real-time server activity logs in the GUI.
- Just download and run, no installation required (for WINDOWS OS only).

## Installation
PortaLocal offers two installation methods:

### 1. Windows EXE (No Installation Required)
- **Platform**: Windows only
- **Steps**:
  1. Download the latest `PortaLocal.exe` from the [Releases](https://github.com/Trqc-Nam/PortaLocal/releases) page.
  2. Double-click the EXE file to run PortaLocal immediately.
  3. No additional installation or dependencies are needed.
- **Note**: Ensure you download from the official GitHub repository for security.

### 2. Source Code Installation
- **Platform**: Windows, macOS, Linux
- **Requirements**:
  - Python 3.6 or higher
  - Python packages: `tkinter` (included with Python), `Pillow`, `PyOpenSSL`
- **Steps**:
  1. Clone the repository:
     ```bash
     git clone https://github.com/Trqc-Nam/PortaLocal.git
     cd PortaLocal
     ```
  2. Install dependencies:
     ```bash
     pip install Pillow PyOpenSSL
     ```
  3. Run the application:
     ```bash
     python PortaLocal.py
     ```

## Usage
1. Launch PortaLocal (via PortaLocal.exe or `python PortaLocal.py`).
2. In the GUI:
   - **Directory**: Click "Browse" to select a folder or enter the path manually.
   - **Port**: Enter a port (e.g., 8000). Ensure it’s between 1024–65535 and not in use.
   - **Protocol**: Select HTTP or HTTPS from the dropdown.
3. Click **Start Server** to launch the server. The address (e.g., `http://localhost:8000`) will be shown.
4. Optionally, open the address in your browser when prompted.
5. Monitor logs in the built-in terminal.
6. Click **Stop Server** to shut down.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a branch (`git checkout -b feature/your-feature`).
3. Commit changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

For details, see [CONTRIBUTING.md](CONTRIBUTING.md). Report issues or suggest features via [GitHub Issues](https://github.com/Trqc-Nam/PortaLocal/issues).

## License
PortaLocal is licensed under the [GNU General Public License v3.0](LICENSE).

## Contact
- **Author**: Trương Quốc Nam
- **Email**: tr.qcnam2k8@gmail.com
- **GitHub**: [Trqc-Nam/PortaLocal](https://github.com/Trqc-Nam/PortaLocal)

---

# PortaLocal - Tạo Localhost Nhanh Chóng

[English](#portalocal---create-localhost-quickly) | **Tiếng Việt**

## Giới Thiệu
PortaLocal là một công cụ giao diện đồ họa thân thiện được phát triển bởi Trương Quốc Nam để tạo và quản lý các máy chủ HTTP/HTTPS cục bộ. Được xây dựng bằng Python và Tkinter, công cụ cho phép người dùng chọn thư mục, chỉ định cổng, chọn giao thức HTTP hoặc HTTPS, và khởi động/dừng máy chủ một cách dễ dàng. Nó hỗ trợ chứng chỉ SSL tự ký cho HTTPS và có terminal tích hợp để xem log máy chủ. PortaLocal là mã nguồn mở theo [Giấy phép Công cộng GNU v3.0](LICENSE).

## Tính Năng
- Khởi động và dừng máy chủ HTTP/HTTPS qua giao diện đồ họa.
- Duyệt hoặc nhập thủ công thư mục để phục vụ nội dung.
- Hỗ trợ HTTP và HTTPS với tạo chứng chỉ tự ký tự động.
- Chọn cổng tùy chỉnh với lưu lịch sử.
- Hiển thị log hoạt động máy chủ trong thời gian thực.
- Chỉ cần tải về và dùng ngay, không cần cài đặt (chỉ WINDOWS OS).


## Cài Đặt
PortaLocal cung cấp hai phương thức cài đặt:

### 1. File EXE cho Windows (Không Cần Cài Đặt)
- **Nền tảng**: Chỉ Windows
- **Hướng dẫn**:
  1. Tải file `PortaLocal.exe` mới nhất từ trang [Releases](https://github.com/Trqc-Nam/PortaLocal/releases).
  2. Nhấp đúp vào file EXE để chạy PortaLocal ngay lập tức.
  3. Không cần cài đặt thêm hoặc phụ thuộc.
- **Lưu ý**: Chỉ tải từ kho GitHub chính thức để đảm bảo an toàn.

### 2. Cài Đặt từ Mã Nguồn
- **Nền tảng**: Windows, macOS, Linux
- **Yêu cầu**:
  - Python 3.6 trở lên
  - Gói Python: `tkinter` (đi kèm Python), `Pillow`, `PyOpenSSL`
- **Hướng dẫn**:
  1. Tải mã nguồn:
     ```bash
     git clone https://github.com/Trqc-Nam/PortaLocal.git
     cd PortaLocal
     ```
  2. Cài đặt phụ thuộc:
     ```bash
     pip install Pillow PyOpenSSL
     ```
  3. Chạy ứng dụng:
     ```bash
     python PortaLocal.py
     ```

## Sử Dụng
1. Khởi động PortaLocal (qua file PortaLocal.exe với Windows OS hoặc `python PortaLocal.py`).
2. Trong giao diện:
   - **Thư mục**: Nhấn "Browse" để chọn thư mục hoặc nhập đường dẫn thủ công.
   - **Cổng**: Nhập số cổng (ví dụ: 8000). Đảm bảo cổng từ 1024–65535 và không bị chiếm dụng.
   - **Giao thức**: Chọn HTTP hoặc HTTPS từ menu thả xuống.
3. Nhấn **Start Server** để khởi động máy chủ. Địa chỉ (ví dụ: `http://localhost:8000`) sẽ hiển thị.
4. Tùy chọn mở địa chỉ trong trình duyệt khi được hỏi.
5. Theo dõi log trong terminal tích hợp.
6. Nhấn **Stop Server** để dừng máy chủ.

## Đóng Góp
Chúng tôi hoan nghênh mọi đóng góp! Để tham gia:
1. Fork kho mã nguồn.
2. Tạo nhánh (`git checkout -b feature/tính-năng-của-bạn`).
3. Commit thay đổi (`git commit -m "Thêm tính năng của bạn"`).
4. Push lên nhánh (`git push origin feature/tính-năng-của-bạn`).
5. Mở Pull Request.

Xem chi tiết tại [CONTRIBUTING.md](CONTRIBUTING.md). Báo lỗi hoặc đề xuất tính năng qua [GitHub Issues](https://github.com/Trqc-Nam/PortaLocal/issues).

## Giấy Phép
PortaLocal được cấp phép theo [Giấy phép Công cộng GNU v3.0](LICENSE).

## Liên Hệ
- **Tác giả**: Trương Quốc Nam
- **Email**: tr.qcnam2k8@gmail.com
- **GitHub**: [Trqc-Nam/PortaLocal](https://github.com/Trqc-Nam/PortaLocal)
