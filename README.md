# TIKI-WEB-SCRAPING
TIKI WEB SCRAPING is a small project to store available products on TIKI Vietnam website. 

The project successfully scraped all products accross all the categories.

# Process
## Data Scrapping:

CODE CAN BE REFERED IN TIKI_WEB_SCRAPPING.ipynb

1) Create categories which include all the type of products in TIKI:

 Name                         | URL           
 ---------------------------- |-------------
| Điện Thoại - Máy Tính Bảng  | https://tiki.vn/dien-thoai-may-tinh-bang/c1789?src=c.1789.hamburger_menu_fly_out_banner |
| Điện Tử - Điện Lạnh         | https://tiki.vn/tivi-thiet-bi-nghe-nhin/c4221?src=c.4221.hamburger_menu_fly_out_banner      |
| Phụ Kiện - Thiết Bị Số      | https://tiki.vn/thiet-bi-kts-phu-kien-so/c1815?src=c.1815.hamburger_menu_fly_out_banner      |
| Laptop - Thiết bị IT        | https://tiki.vn/laptop-may-vi-tinh/c1846?src=c.1846.hamburger_menu_fly_out_banner |
| Máy Ảnh - Quay Phim         | https://tiki.vn/may-anh/c1801?src=c.1801.hamburger_menu_fly_out_banner      |
| Điện Gia Dụng               | https://tiki.vn/dien-gia-dung/c1882?src=c.1882.hamburger_menu_fly_out_banner  |
| Nhà Cửa Đời Sống            | https://tiki.vn/nha-cua-doi-song/c1883?src=c.1883.hamburger_menu_fly_out_banner |
| Hàng Tiêu Dùng - Thực Phẩm  | https://tiki.vn/bach-hoa-online/c4384?src=c.4384.hamburger_menu_fly_out_banner      |
| Đồ chơi, Mẹ & Bé            | https://tiki.vn/me-va-be/c2549?src=c.2549.hamburger_menu_fly_out_banner      |
| Làm Đẹp - Sức Khỏe          | https://tiki.vn/lam-dep-suc-khoe/c1520?src=c.1520.hamburger_menu_fly_out_banner |
| Xe Máy, Ô tô, Xe Đạp        | https://tiki.vn/o-to-xe-may-xe-dap/c8594?src=c.8594.hamburger_menu_fly_out_banner      |
| Hàng quốc tế                | https://tiki.vn/hang-quoc-te/c17166?src=c.17166.hamburger_menu_fly_out_banner      |
| Sách, VPP & Quà Tặng        | https://tiki.vn/nha-sach-tiki/c8322?src=c.8322.hamburger_menu_fly_out_banner |
| Voucher - Dịch Vụ - Thẻ Cào | https://tiki.vn/voucher-dich-vu/c11312?src=c.11312.hamburger_menu_fly_out_banner      |

2) Create function to get information from one product:
These information is include:

Number  | Information           
--------|-------------
| 1     | Name      
| 2     | Price             
| 3     | product_url      
| 4     | Image 
| 5     | Freeship      
| 6     | Rating
| 7     | Badge_Under_Price
| 8     | Be_Paid_By_Installments
| 9     | Free_Gifts

3) Create function to scrap all the info of all products from a Page URL and start scrapping

4) All the information is store in tiki_products.csv
