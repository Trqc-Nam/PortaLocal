# Contributing to PortaLocal

**English** \| [Tiếng Việt](#đóng-góp-vào-portalocal)

Thank you for your interest in contributing to **PortaLocal**, a GUI
tool for creating local HTTP/HTTPS servers, developed by Trương Quốc
Nam. We welcome contributions from the community to enhance the project.
This document outlines how to contribute effectively.

## How to Contribute

Follow these steps to contribute to PortaLocal:

1.  **Fork the Repository**:

    -   Visit <https://github.com/Trqc-Nam/PortaLocal> and click the
        "Fork" button to create a copy in your GitHub account.

2.  **Clone Your Fork**:

    ``` bash
    git clone https://github.com/<your-username>/PortaLocal.git
    cd PortaLocal
    ```

3.  **Create a Branch**:

    -   Create a new branch for your changes:

        ``` bash
        git checkout -b feature/your-feature-name
        ```

    -   Use descriptive branch names (e.g., `fix/bug-description`,
        `feature/new-functionality`).

4.  **Make Changes**:

    -   Implement your feature, bug fix, or improvement.
    -   Ensure your code follows the [Coding
        Guidelines](#coding-guidelines) below.
    -   Test your changes thoroughly.

5.  **Commit Changes**:

    -   Write clear, concise commit messages:

        ``` bash
        git commit -m "Add feature: describe your change"
        ```

6.  **Push to Your Fork**:

    ``` bash
    git push origin feature/your-feature-name
    ```

7.  **Open a Pull Request**:

    -   Go to the [PortaLocal
        repository](https://github.com/Trqc-Nam/PortaLocal) and open a
        Pull Request from your branch.
    -   Provide a detailed description of your changes, including the
        purpose and any relevant issue numbers.
    -   The maintainer (Trương Quốc Nam) will review your Pull Request
        and provide feedback.

## Reporting Issues

If you find bugs or have feature requests: - Open an issue on the
[GitHub Issues page](https://github.com/Trqc-Nam/PortaLocal/issues). -
Include: - A clear title and description. - Steps to reproduce the issue
(if applicable). - Expected and actual behavior. - Screenshots or logs,
if relevant.

## Coding Guidelines

To ensure consistency and quality: - **Language**: Write code in Python
3.6+. - **Style**: Follow [PEP
8](https://www.python.org/dev/peps/pep-0008/) for Python code. -
**Dependencies**: Avoid adding new dependencies unless necessary.
Current dependencies are `tkinter`, `Pillow`, and `PyOpenSSL`. -
**Testing**: Test your changes on supported platforms (Windows, macOS,
Linux). - **Documentation**: Update the `README.md` or other
documentation if your changes affect usage or installation. -
**License**: Ensure all contributions comply with the [GNU GPL
v3.0](LICENSE).

## Code of Conduct

-   Be respectful, inclusive, and collaborative in all interactions.
-   Avoid offensive language or behavior.
-   We aim to maintain a welcoming community for all contributors.

## Contact

For questions or support: - **Author**: Trương Quốc Nam - **Email**:
tr.qcnam2k8@gmail.com - **GitHub Issues**:
<https://github.com/Trqc-Nam/PortaLocal/issues>

Thank you for helping improve PortaLocal!

------------------------------------------------------------------------

# Đóng Góp vào PortaLocal

[English](#contributing-to-portalocal) \| **Tiếng Việt**

Cảm ơn bạn đã quan tâm đến việc đóng góp cho **PortaLocal**, một công cụ
giao diện đồ họa để tạo máy chủ HTTP/HTTPS cục bộ, được phát triển bởi
Trương Quốc Nam. Chúng tôi hoan nghênh mọi đóng góp từ cộng đồng để cải
thiện dự án. Tài liệu này hướng dẫn cách đóng góp hiệu quả.

## Cách Đóng Góp

Thực hiện các bước sau để đóng góp cho PortaLocal:

1.  **Fork Kho Mã Nguồn**:

    -   Truy cập <https://github.com/Trqc-Nam/PortaLocal> và nhấn nút
        "Fork" để tạo bản sao trên tài khoản GitHub của bạn.

2.  **Tải Bản Sao Fork**:

    ``` bash
    git clone https://github.com/<tên-người-dùng-của-bạn>/PortaLocal.git
    cd PortaLocal
    ```

3.  **Tạo Nhánh**:

    -   Tạo nhánh mới cho thay đổi của bạn:

        ``` bash
        git checkout -b feature/tên-tính-năng-của-bạn
        ```

    -   Sử dụng tên nhánh mô tả (ví dụ: `fix/mô-tả-lỗi`,
        `feature/chức-năng-mới`).

4.  **Thực Hiện Thay Đổi**:

    -   Triển khai tính năng, sửa lỗi hoặc cải tiến.
    -   Đảm bảo mã của bạn tuân theo [Hướng Dẫn Viết
        Mã](#hướng-dẫn-viết-mã) bên dưới.
    -   Kiểm tra kỹ lưỡng các thay đổi.

5.  **Commit Thay Đổi**:

    -   Viết thông điệp commit rõ ràng, ngắn gọn:

        ``` bash
        git commit -m "Thêm tính năng: mô tả thay đổi của bạn"
        ```

6.  **Push Lên Fork**:

    ``` bash
    git push origin feature/tên-tính-năng-của-bạn
    ```

7.  **Mở Pull Request**:

    -   Truy cập [kho
        PortaLocal](https://github.com/Trqc-Nam/PortaLocal) và mở Pull
        Request từ nhánh của bạn.
    -   Cung cấp mô tả chi tiết về thay đổi, bao gồm mục đích và số
        issue liên quan (nếu có).
    -   Người duy trì (Trương Quốc Nam) sẽ xem xét Pull Request và phản
        hồi.

## Báo Cáo Lỗi

Nếu bạn tìm thấy lỗi hoặc có đề xuất tính năng: - Mở issue trên [trang
GitHub Issues](https://github.com/Trqc-Nam/PortaLocal/issues). - Bao
gồm: - Tiêu đề và mô tả rõ ràng. - Các bước để tái hiện lỗi (nếu có). -
Hành vi kỳ vọng và hành vi thực tế. - Ảnh chụp màn hình hoặc log, nếu
liên quan.

## Hướng Dẫn Viết Mã

Để đảm bảo tính nhất quán và chất lượng: - **Ngôn ngữ**: Viết mã bằng
Python 3.6+. - **Phong cách**: Tuân theo [PEP
8](https://www.python.org/dev/peps/pep-0008/) cho mã Python. - **Phụ
thuộc**: Tránh thêm phụ thuộc mới trừ khi cần thiết. Phụ thuộc hiện tại
là `tkinter`, `Pillow`, và `PyOpenSSL`. - **Kiểm tra**: Kiểm tra thay
đổi trên các nền tảng hỗ trợ (Windows, macOS, Linux). - **Tài liệu**:
Cập nhật `README.md` hoặc tài liệu khác nếu thay đổi ảnh hưởng đến cách
sử dụng hoặc cài đặt. - **Giấy phép**: Đảm bảo mọi đóng góp tuân thủ
[GNU GPL v3.0](LICENSE).

## Quy Tắc Ứng Xử

-   Tôn trọng, hòa nhập và hợp tác trong mọi tương tác.
-   Tránh ngôn ngữ hoặc hành vi xúc phạm.
-   Chúng tôi hướng đến duy trì một cộng đồng thân thiện cho tất cả.

## Liên Hệ

Để được hỗ trợ hoặc có câu hỏi: - **Tác giả**: Trương Quốc Nam -
**Email**: tr.qcnam2k8@gmail.com - **GitHub Issues**:
<https://github.com/Trqc-Nam/PortaLocal/issues>

Cảm ơn bạn đã giúp cải thiện PortaLocal!
