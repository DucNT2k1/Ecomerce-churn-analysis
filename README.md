# Ecomerce churn analysis
# :books: Table of Contents <!-- omit in toc -->

- [:briefcase: Dataset and Requirement](#dataset-and-requirement)
- [:bookmark_tabs: Dataset Information](#bookmark_tabsdataset-information)
- [🔎 Clean data then make operational report and dashboard](#--clean-data-then-make-operational-report-and-dashboard)

---

# Dataset and Requirement
The data set belongs to a leading online E-Commerce company, contain information

Dataset contains information about the operations of a Vietnamese company in the third quarter of 2020, including 3 tables:
- MKT: Contains information about Marketing activities
- Sales: Contains information about sales activities
- Vận đơn: Contains information about bill of lading activities 
### ❓ Question
Can you predict whether customers will churn based on customer data ?

---
# :bookmark_tabs:Dataset Information

<details><summary> 👆🏼 MKT table </summary>

This data has 21 columns, including:

- Date:The date the marketing campaign was implemented
- Channel: Channel used to display ads
- MKTer: Name of staff member
- Chiến dịch: Name of marketing campaign
- Chi phí Marketing: Marketing expense
- Impression: Number of ad impressions
- Reach: Total number of unique individuals exposed to the ad
- Click: Number of clicks on ad
- Share: Number of shares
- Cmt: Number of comments
- Inbox: Number of inboxs
- Lead MKT: Number of Leads
- Đơn hàng: Numbers of orders
- Doanh thu: Revenue
- Paid Revenue 1: revenue generated from products that were sold through marketing campaign
- Giá/Lead: Expense per Lead
- Đơn/Lead: Order per Lead
- CPM: Expense per 1000 Impressions
- CPC: Expense per Click
- Giá Mess\n(Cmt + Inbox): Expense per Cmt or Inbox
- Mục danh sách: Total marketing expenses and taxes

 

</details>

<details><summary> 👆🏼 Sales table </summary>

Data has 21 columns, including:

- 'Unnamed: 0' : Unclear
- Giờ: The time that customers leave their information on the ads
- Khách hàng: Name of Lead
- SĐT: Number phone of Lead
- Channel: Channel which customer is advertised
- Chiến dịch: Marketing campaign which customer is advertised
- Content: Unclear
- Marketer 2: Name of marketer
- Type of Lead: Type of Lead, includes 2 values: Dathang(ordered) and Tuvan (being consulted)
- Sales Admin xác nhận Type of Lead: Confirmation of type of Lead by Sales Admin
- Sales: Name of Sales
- Số lần tương tác: Number of calls
- Ngày gọi: The day the employee contacted the Lead
- Trạng thái: Lead status
- Level: Lead status in more detail
- Ngày hẹn gọi lại: The date the customer makes an appointment to call back
- Close date: The date the customer completes payment
- Tỉnh/TP: Province/City where the customer lives
- Số lượng bộ sách: Number of book sets ordered
- Số tiền giảm giá: Discount amount
- Tổng tiền: Total amount that the customer needs to pay

</details>

<details><summary> 👆🏼 Vận đơn table </summary>
 This data has 45 columns, including:

- STT: serial number column
- Mã đơn hàng: code orders
- Ghi chú đơn hàng: order notes
- Tags đơn hàng: order tags
- Nhân viên tạo đơn: Name of the employee creating the order
- Chi nhánh: branch
- Nguồn: source
- Mã vận đơn: bill of lading code
- Tình trạng gói hàng: order status
- Trạng thái đối tác: shipping partner status
- Lý do hủy đơn: reason for cancellation
- Ngày đóng gói: the date the order was packed
- Ngày hẹn giao hàng: delivery appointment date
- Ngày xuất kho: date of inventory
- Ngày giao hàng: delivery date
- Đối tác giao hàng: name of shipping partner company
- Dịch vụ giao hàng: name of delivery service
- Khối lượng: package volume
- Kích thước(DxRxC): package size
- Tên người nhận: name of consignee
- SĐT người nhận: number phone of consignee
- Địa chỉ giao hàng: delivery address
- Tỉnh/Thành: the province where the customer lives
- Quận/Huyện: the district where the customer lives
- Phường xã: the ward where the customer lives
- Trạng thái đối soát: Control status
- Tiền khách phải trả cho đơn: the amount the customer must pay
- Khách hàng đã trả: the amount the customer has paid
- Hình thức thanh toán: payments
- Tổng tiền thu hộ: total amount collected
- Phí vận chuyển: transport expense
- Người trả phí: the party must pay the fee
- Phí trả đối tác: the expense paid to partner company
- Ghi chú đơn giao: notes for carrier
- Mã sản phẩm: product code
- Tên sản phẩm: product name
- Ghi chú sản phẩm: product note
- Serial: Unclear
- Đơn vị tính: unit
- Đơn giá: unit price
- CK sản phẩm: product discount
- CK tổng đơn hàng: order discount
- Thuế cho từng sản phẩm: tax for each product
- Tổng tiền hàng: total order amount
</details>  

---

## 🔎  Clean data then make operational report and dashboard

### The Process is following 
- [Cleaning data](https://colab.research.google.com/drive/1yyFx9yizeurIivMRMfWL0qw66xMab9SN?hl=vi)
- [Operational Report](https://1drv.ms/b/c/cec2721c7222ade2/EauLpQgt5V1KhRSgeqEgGHoBPFZLdyjDjEI6-tx9832KVA?e=t7aota) 
- [Dashboard](https://github.com/DucNT2k1/Build-operational-reports-and-dashboards-for-businesses/blob/main/Dashboard.pbix)
