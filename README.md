# BÁO CÁO THỰC HÀNH MÔN TRÍ TUỆ NHÂN TẠO

- **Họ và tên:** Đặng Quang Minh
- **MSSV:** 2001230522

---

## 📝 Giới thiệu
Repository này là nơi lưu trữ báo cáo và mã nguồn các bài thực hành môn **Trí tuệ Nhân tạo**. Dự án bao gồm các thuật toán tìm kiếm, các trò chơi đối kháng và bài toán tối ưu hóa trên đồ thị.

## 📂 Danh sách bài thực hành

### 1. Bài tập 1: Giải bài toán N-Puzzle (Trò chơi trượt số)
Sử dụng thuật toán tìm kiếm để đưa bảng số từ trạng thái ngẫu nhiên về trạng thái đích.
- **Thuật toán:** Branch and Bound (Nhánh và Cận) / A* Search.
- **Tính năng:**
  - Hỗ trợ nhập kích thước bàn cờ $N \times N$ (3x3, 4x4...).
  - Sử dụng Heuristic (số ô sai vị trí) để tìm đường đi tối ưu.
  - In ra từng bước di chuyển để dẫn đến kết quả.
- **Thư mục:** Akt và A*.ipynb
- **Demo:**

<img width="1208" height="699" alt="image" src="https://github.com/user-attachments/assets/92c06eaa-9c68-47fc-b786-850107c4b073" />



### 2. Bài tập 2: Cờ Caro (Tic-Tac-Toe) $N \times N$ với AI
Xây dựng AI chơi cờ Caro bất bại (hoặc khó đánh bại) với người chơi.
- **Thuật toán:** Minimax kết hợp Cắt tỉa Alpha-Beta (Alpha-Beta Pruning).
- **Tính năng:**
  - Tùy chỉnh kích thước bàn cờ (3x3, 4x4, 5x5...).
  - **Giới hạn độ sâu (Depth Limit):** Giúp AI tính toán nhanh kể cả với bàn cờ lớn ($4 \times 4$ trở lên).
  - Giao diện Console trực quan, hiển thị bàn cờ sau mỗi nước đi.
- **Thư mục:** Minimax và Alpha-beta.ipynb
- **Demo:**
  <img width="332" height="375" alt="image" src="https://github.com/user-attachments/assets/175f3e31-13ed-4114-97f6-125c829a1ff2" />          <img width="229" height="437" alt="image" src="https://github.com/user-attachments/assets/233671ae-2b53-42d7-a73d-809085a76d6e" />



### 3. Bài tập 4: Phân cụm K-Means & Phân loại K-NN
Triển khai hai thuật toán học máy cơ bản (Machine Learning) để xử lý dữ liệu và trực quan hóa kết quả phân lớp.
- **Phần A: K-Means Clustering (Phân cụm)**
  - **Mục tiêu:** Gom nhóm các điểm dữ liệu chưa được dán nhãn thành $K$ cụm dựa trên độ tương đồng.
  - **Thuật toán:** Học không giám sát (Unsupervised) - Di chuyển tâm cụm (Centroids) lặp lại để tối ưu hóa khoảng cách.
- **Phần B: K-Nearest Neighbors (K-NN)**
  - **Mục tiêu:** Dự đoán nhãn (class) của một điểm dữ liệu mới dựa trên $K$ điểm hàng xóm gần nhất.
  - **Thuật toán:** Học có giám sát (Supervised) - Tính khoảng cách và bầu chọn theo đa số (Majority Voting).
- **Thư mục:** K-Mean và KNN.ipynb
- **Demo:**

  <img width="518" height="426" alt="image" src="https://github.com/user-attachments/assets/325c6802-85da-4945-b22f-889ca40bb64a" />

  <img width="512" height="335" alt="image" src="https://github.com/user-attachments/assets/23a9e3ac-39e1-44f3-a9ba-556c01c8303c" />
 
  <img width="460" height="342" alt="image" src="https://github.com/user-attachments/assets/2583991f-7215-4eb8-90a3-c9dfbad4e9b7" />
 
  <img width="476" height="346" alt="image" src="https://github.com/user-attachments/assets/bd44a080-577a-42f8-aaff-0615e9943e42" />

  <img width="477" height="357" alt="image" src="https://github.com/user-attachments/assets/c7402cc4-0249-49eb-9b83-ea9d23d8ec1b" />
 
  <img width="473" height="338" alt="image" src="https://github.com/user-attachments/assets/36987df0-b6d5-47d3-b8c0-72fbd7daafe7" />
 
  <img width="452" height="333" alt="image" src="https://github.com/user-attachments/assets/62c7201d-79c5-4897-b2be-cba25ade9e1f" />

  <img width="461" height="330" alt="image" src="https://github.com/user-attachments/assets/9abc41fe-f524-4188-aa98-05be5a3ce272" />
  
  <img width="450" height="412" alt="image" src="https://github.com/user-attachments/assets/9dfc2d37-ab6d-4773-ad15-f7e73410422b" />


### demo của KNN
<img width="653" height="443" alt="image" src="https://github.com/user-attachments/assets/5bdf8c80-63d9-4caf-b0fc-816e0b3b03db" />
<img width="688" height="426" alt="image" src="https://github.com/user-attachments/assets/cdacf18f-29d3-4c97-b1d1-d3a4fd0d8d01" />
<img width="649" height="412" alt="image" src="https://github.com/user-attachments/assets/1281e850-9f52-4f8e-82fd-694e72d4d536" />
<img width="662" height="427" alt="image" src="https://github.com/user-attachments/assets/34be3ad0-3160-4944-ae7e-36b4e8fd4021" />
<img width="633" height="424" alt="image" src="https://github.com/user-attachments/assets/e070ccee-b5fc-4b42-a339-0f45c4eb8e4f" />


