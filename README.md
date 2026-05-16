# Chat_Doctor

Dự án fine-tuning mô hình ngôn ngữ lớn (LLM) cho lĩnh vực y tế. Repository này chứa các Jupyter Notebook phục vụ cho quá trình chuẩn bị dữ liệu, sửa nhãn, tạo mask và suy luận với mô hình đã fine-tune.

---

## Mục lục
- [Tổng quan](#tổng-quan)
- [Cấu trúc thư mục](#cấu-trúc-thư-mục)
- [Hướng dẫn sử dụng](#hướng-dẫn-sử-dụng)
- [Notebook chính](#notebook-chính)
- [Yêu cầu môi trường](#yêu-cầu-môi-trường)
- [Ghi chú](#ghi-chú)

---

## Tổng quan

Dự án này tập trung vào việc fine-tune mô hình LLM cho các tác vụ liên quan đến lĩnh vực y tế.  
Các notebook trong thư mục `Source/` đảm nhiệm nhiều bước khác nhau trong pipeline xử lý dữ liệu và huấn luyện mô hình, bao gồm:

- Tiền xử lý dữ liệu
- Sửa và chuẩn hóa label
- Tạo mask cho dữ liệu huấn luyện
- Dịch và xử lý dữ liệu mẫu
- Kiểm thử và suy luận với mô hình đã fine-tune

---

## Cấu trúc thư mục

```bash
Chat_Doctor/
│
├── README.md
│
└── Source/
    ├── fix-label.ipynb
    ├── fushion-mask-model.ipynb
    ├── make-mask.ipynb
    ├── translate-sample-3000.ipynb
    └── using-my-finetunemodel.ipynb