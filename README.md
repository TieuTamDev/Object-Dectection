#### HƯỚNG DẪN CÀI ĐẶT VÀ CÁC CHÚ Ý LIÊN QUAN ####
- Chào mọi người, mình là TieuTamDev - 1 trong những thành viên của project này. Sau đây có một số chú ý khi cài đặt.

1. Các file mô hình đều do nhiều thành viên làm và gộp lại điều thành 1 file code nên khi chạy chú ý chạy từng mô hình một.

    -1.1. Các mô hình transfer learning có thể bị trùng tên với mô hình tự xây dựng cho nên vui lòng sau khi chạy xong các mô hình tự xây
    dựng thì hãy reset kernel chạy lại từ đầu với data và mô hình transfer learning.
   
    -1.2. File tổng hợp được chạy trên Jupyter Notebook trên nền tảng Anaconda. Vui lòng điều chỉnh cho phù hợp khi chuyển đổi môi trường
    chạy.
    
3. Đối với streamlit để hỗ trợ xây dựng web thì cần đảm bảo như sau:

    -2.1. Đảm bảo file xây dựng code web được lưu dưới dạng .py của python. (Như mình là Segmentation.py và Webapp.py trong đó: Segmentation.py là chứa
    giao diện web của Segmenttation còn Webapp.py là classifi của các model huấn luyện khác.)
   
    -2.2. Đảm bảo môi trường chạy phải cung cấp đầy đủ các thư viện liên quan đến mô hình và web.
   
    -2.3. Mở terminal -> chuyển đến nơi lưu file code web bằng lệnh sau [cd "đường dẫn thư mục chứa file code"] ->sau đó nhập lệnh
    [streamlit run 'tên file code.py'].
   
    *Lưu ý: Phải đảm bảo môi trường đầy đủ các thư viện. Ví dụ ở đây mình sử dụng Anaconda với môi trường chạy là my_env nơi cài đặt đủ thư
    viện cho nên ở bước terminal mình sẽ chạy thêm lệnh [conda activate my_env] để kích hoạt môi trường.

5. Đối với file code U-net Segmentation.ypnb thì dữ liệu train là file Data-2 với các file liên quan nằm trong đó.


!!!!!!! Cảm ơn đã đọc !!!!!!!!!
