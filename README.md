# Khao-sat-Ung-dung-Chabot-thong-minh-de-ho-tro-hoc-tap-cua-hoc-sinh
Khảo sát mức độ hài lòng của giáo viên và học sinh khi sử dụng AI/Chatbot trong học tập, rèn luyện. Lưu trữ bộ câu hỏi, dữ liệu và phân tích khảo sát trên Google Form về Chatbot hỗ trợ học tập
# Bộ dữ liệu khảo sát chất lượng tập huấn "Ứng dụng AI trong giáo dục và đổi mới"

## 1. Giới thiệu

Kho lưu trữ này dùng để lưu trữ **bộ câu hỏi, dữ liệu và phân tích** của khảo sát
chất lượng tập huấn *"Ứng dụng AI trong giáo dục và đổi mới"* được thực hiện với
hai nhóm đối tượng chính:

- Giáo viên
- Học sinh

Dữ liệu được thu thập bằng Google Form, xuất ra file Excel và được ẩn danh khi công bố.

## 2. Cấu trúc thư mục

- `data/raw/`  
  - Chứa dữ liệu gốc xuất từ Google Form, ví dụ:  
    `KHẢO SÁT CHẤT LƯỢNG TẬP HUẤN_ỨNG DỤNG AI TRONG GIÁO DỤC VÀ ĐỔI MỚI_Responses.xlsx`

- `data/clean/`  
  - Chứa dữ liệu đã làm sạch, mã hóa thang đo (nếu có), ví dụ:  
    `data_clean.csv`

- `docs/`  
  - `PHU_LUC_KHAO_SAT.md`: Phụ lục bộ câu hỏi khảo sát và bảng mã hóa biến (codebook).  
  - `mo_ta_du_lieu.md`: Mô tả chi tiết cách thu thập, xử lý và sử dụng dữ liệu.

- `analysis/`  
  - Các notebook hoặc script phân tích dữ liệu (Python/R), ví dụ:  
    `phan_tich_khaosat.ipynb`.

## 3. Ghi chú về đạo đức và bảo mật

- Dữ liệu công bố đã được **ẩn danh** (không chứa tên, số điện thoại hoặc thông tin nhận dạng cá nhân trong bản public).
- Khi sử dụng dữ liệu này cho nghiên cứu hoặc trích dẫn trong luận văn, bài báo,
  vui lòng ghi rõ nguồn và không cố gắng truy ngược danh tính người tham gia.

## 4. Liên hệ

Mọi câu hỏi liên quan đến bộ dữ liệu, phương pháp khảo sát và phân tích,
vui lòng liên hệ với tác giả luận văn.
