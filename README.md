# it-asset-manager
> Học thêm nữa để có kỹ năng đi tà đạo, ăn trộm cũng phải có chuyên môn mà 🤣

## Chức năng

            ┌──────────────┐
            │   Web UI     │
            │              │
            │ Thiết bị     │
            │ Tìm kiếm     │
            │ Thêm / sửa   │
            │ Xóa          │
            └──────┬───────┘
                   │
                   ▼
            ┌──────────────┐
            │   FastAPI    │
            │     API      │
            └──────┬───────┘
                   │
                   ▼
            ┌──────────────┐
            │ PostgreSQL   │
            │              │
            │ devices      │
            │ employees    │
            │ software     │
            │ history      │
            └──────┬───────┘
                   │
      ┌────────────┴────────────┐
      ▼                         ▼
Import Excel               Export Excel

- Website quản lý thiết bị cty.
- Thêm, xóa, sửa thiết bị.
- Có thể import và export data thông qua file excel.
- ...

## Installation

- Python
- Nodejs

```bash
git clone <repo>
cd project
npm install
