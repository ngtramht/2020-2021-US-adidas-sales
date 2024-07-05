# ADIDAS US SALES 2020-2021
## Giới thiệu
Mục đích của dự án nhằm phân tích hiệu suất bán hàng, doanh thu lợi nhuận của Adidas tại Mỹ vào khoảng thời gian 2020-2021, giai đoạn đại dịch Covid bùng nổ. Việc phân tích dựa trên thông tin bộ dữ liệu cung cấp bao gồm chi tiết nhà bán lẻ, ngày lập hóa đơn, khu vực, tiểu bang, thông tin sản phẩm, giá mỗi đơn vị, số lượng hàng đã bán, tổng doanh thu và lợi nhuận vào năm nửa sau năm 2020 và năm 2021. 
## Phương pháp
### Tiền xử lí dữ liệu
Dựa vào bộ dữ liệu này ta cần tiến hành xử lí để chuẩn bị cho việc phân tích. Đầu tiên thực hiện các bước kiểm tra và xử lí giá trị trùng lặp, dữ liệu bị thiếu, xử lí outliers, tạo và xóa các thuộc tính và chuyển kiểu dữ liệu phù hợp cho quá trình phân tích.
### Phân tích và trực quan dữ liệu
Thư viện sử dụng:
- NumPy
- Pandas
- Matplotlib
- Seaborn

### Data source
link Kaggle [https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset/data](url)

### Thuộc tính dữ liệu

1	Retailer: Tên các đại lý phân phối sản phẩm của Adidas.
2	Retailer ID: Mã định danh của các đại lý.
3	Invoice Date: Thời gian bán hàng được ghi trên hóa đơn.
4	Region: Khu vực bán hàng của Adidas tại Mỹ.
5	State: Tiểu bang nơi các có các cửa hàng phân phối các sản phẩm của Adidas
6	City:	Tên các thành phố 
7	Product:	Tên sản phẩm được bán của Adidas
8	Price per Unit: Giá trên mỗi đơn vị sản phẩm được bán ra.
9	Units Sold: Số lượng sản phẩm đã được bán ra trên mỗi hóa đơn.
10	Operating Profit: Lợi nhuận hoạt động
11	Operating Margin: Biên lợi nhuận của mỗi hóa đơn
12	Sales Method: Các phương thức bán hàng.

