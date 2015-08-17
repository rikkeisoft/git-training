## [Rikkeisoft] Git Training

- Hướng dẫn về Git cơ bản cho người mới bắt đầu: Đọc ở [đây](http://backlogtool.com/git-guide/vn/intro/intro1_1.html) (Tiếng Việt)
- Sổ tay về Git: Đọc ở [đây](http://rogerdudler.github.io/git-guide/index.vi.html) (Tiếng Việt)
- Thực hành những thao tác căn bản với Git online: [Try Git](http://try.github.com/)  (Tiếng Anh)
- Những lệnh hay dùng: [Git Cheatsheet](http://www.git-tower.com/blog/git-cheat-sheet/)  (Tiếng Anh)
- Ebook hướng dẫn Git từ căn bản đến nâng cao: [Tiếng Anh](https://git-scm.com/book/en/v2) (updated 2014), [Tiếng Việt](https://git-scm.com/book/vi/v1) (updated 2009)
- Hướng dẫn sử dụng Git trên Netbean IDE: Đọc ở [đây](https://netbeans.org/kb/docs/ide/git.html)

## Git Client
Dưới đây là những phần mềm tương tác với Git qua giao diện đồ hoạ:
- [SourceTree](http://www.sourcetreeapp.com/) (Windows, Mac)
- [GitExtension](https://github.com/gitextensions/gitextensions/releases) (Windows, Mac, Linux)
- [git-cola](http://git-cola.github.com/) (Windows, Linux)


## Cài đặt Git
- Windows: [Download](https://git-scm.com/book/vi/v1/B%E1%BA%AFt-%C4%90%E1%BA%A7u-C%C3%A0i-%C4%90%E1%BA%B7t-Git#Cài-Đặt-Trên-Windows)
- Linux: [Download](https://git-scm.com/book/vi/v1/B%E1%BA%AFt-%C4%90%E1%BA%A7u-C%C3%A0i-%C4%90%E1%BA%B7t-Git#Cài-Đặt-Trên-Linux)
- Mac: [Download](https://git-scm.com/book/vi/v1/B%E1%BA%AFt-%C4%90%E1%BA%A7u-C%C3%A0i-%C4%90%E1%BA%B7t-Git#Cài-Đặt-Trên-Mac)

## Cấu hình Git căn bản
Thiết lập thông tin cá nhân cho Git: (Sử dụng Git Bash hoặc Terminal để gõ các lệnh sau) **bắt buộc**
- `git config --global user.name "Tên của bạn"`
- `git config --global user.email tên@rikkeisoft.com`

- `git config --global core.safecrlf true`
- `git config --global color.ui true`
- `git config --global core.filemode false`

- `git config --global core.autocrlf input` (Cho Linux - Mac)
- `git config --global core.autocrlf true` (Cho Windows)

## Những điều chú ý khi dùng Git
- Viết nội dung commit có ý nghĩa và liên quan tới công việc đang làm.
 + Ví dụ: Issue #69, có yêu cầu: *"Viết chức năng đăng ký user cho hệ thống"* thì khi commit nên viết message là: **"Implement user registration feature #69"**
