# Mars Robot Explorer

## Giới thiệu

Dự án mô phỏng Robot Thám Hiểm Sao Hỏa sử dụng các thuật toán Trí tuệ Nhân tạo (AI) để thu thập mẫu vật trên bản đồ và quay về căn cứ.

## Mục tiêu

* Thu thập tất cả mẫu vật trên bản đồ.
* Tìm đường đi tối ưu.
* So sánh hiệu quả của các thuật toán AI khác nhau.

## Các thuật toán được sử dụng

### Uninformed Search

* BFS (Breadth First Search)
* DFS (Depth First Search)

### Informed Search

* Greedy Search
* A* Search

### Local Search

* Hill Climbing
* Simulated Annealing

### Constraint Satisfaction Problem (CSP)

* Backtracking
* Forward Checking

## Công nghệ sử dụng

* Python
* Pygame

## Cấu trúc thư mục

algorithms/

* uninformed.py
* informed.py
* local.py
* csp.py

main.py
utils.py

## Cách chạy chương trình

Cài đặt thư viện:

pip install pygame

Chạy chương trình:

python main.py

## Chức năng

* Sinh bản đồ ngẫu nhiên.
* Hiển thị robot, mẫu vật và căn cứ.
* Địa hình đặc biệt có chi phí di chuyển cao hơn.
* Minh họa quá trình tìm kiếm bằng animation.
* Hiển thị thống kê số bước, chi phí và thời gian chạy.

## Môn học

Trí tuệ nhân tạo (Artificial Intelligence)
