# CNPM_PhanHocam_lab_7
Quản lý khách sạn
Xác định yêu cầu đặc tả Goals và business objective
	* Phần mềm dạng ứng dụng cho máy tính cá nhân, chỉ có nhân viên lễ tân, nhân viên bán hàng, quản lý khách sạn được sử dụng, tuy nhiên
    phần mềm cho phép khách hàng có thể sử dụng phần mềm để xem thông tin về khách sạn cũng như là phòng ở trước khi đặt phòng hoặc để 
    dùng một số dịch vụ khác của khách sạn.
	* Người quản lý khách sạn (Manager): Quản lý thông tin phòng và khách sạn (room manager), tạo và xem các loại báo cáo (create report).
	* Nhân viên bán hàng (Saller): Giao dịch với khách hàng(client) qua điện thoại để đặt chỗ (Book a room) hoặc hủy đặt phòng 
    (cancal a booking).
	* Nhân viên tiếp tân (Receptionist): Giao dịch trực tiếp với khách hàng (Client) tại quầy đặt chỗ (Book a room), hủy đặt chỗ 
    (cancel a booking), nhận Checkin, Checkout và thanh toán cho khách hàng.
	* Khách hàng (Client): có thể đặt phòng/hủy phòng (Book a room/Cancel a Booking) trực tiếp tại quầy với nhân viên lễ tân hoặc đặt/hủy 
    qua điện thoại với nhân viên bán hàng. Checkin, Checkout và thanh toán tại quầy với nhân viên lễ tân.
	* Trong khách sạn có nhiều phòng, mỗi phòng được mô tả bằng các thông tin: tên phòng (primary key), loại phòng, giá niêm yết, các loại
    dịch vụ đi kèm, mô tả phòng.
	* Mỗi khách hàng khi đến ở hoặc đặt phòng sẽ được lưu lại các thông tin: số CMND, họ và tên,  số điện thoại, ghi chú về yêu cầu của 
    khách hàng.
	* Mỗi phòng có thể được đặt bởi nhiều khách hàng ở nhiều thời điểm khác nhau.
	* Mỗi khách hàng có thể đặt / ở nhiều phòng khác nhau tại những thời điểm khác nhau
	* Tại một thời điểm,  chỉ có một khách hàng ở trong một phòng.
	* Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong thời gian khách hàng muốn đặt.
	* Khách hàng có thể thanh toán nhiều lần cho đến khi trả phòng.
	* Mỗi lần thanh toán lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin: Họ và tên, số phòng, ngày đến, ngày đi, giá phòng,
    dịch vụ đi kèm, số tiền thanh toán.
	* Khách hàng có thể hủy đặt phòng nếu hủy trước ngày đến.
	* Mục tiêu tổng quan: đảm bảo sự phát triển chung của cả khách sạn.
	* Mục tiêu cụ thể: đảm bảo khả năng sinh lợi nhuận từ việc kinh doanh.
	* Đặt ra mục tiêu nhiệm vụ là phải phấn đấu nâng cao chất lượng dich vụ để làm hài lòng khách hàng, đặc biệt là các khách hàng quen thuộc.
	* Có thể phát triển khối khách sạn ra các chi nhánh ở trong nước cũng như nước ngoài.
