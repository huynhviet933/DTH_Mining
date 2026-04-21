# DTH_Mining
HƯỚNG DẪN CHẠY TOOL DELTAHASH AUTO MINING

1. CÀI ĐẶT MÔI TRƯỜNG
- Mở CMD tại thư mục chứa file main.js và chạy lệnh cài đặt thư viện:
  npm install axios chalk socks-proxy-agent https-proxy-agent node-machine-id
  hoặc npm install

2. CHUẨN BỊ CÁC FILE DỮ LIỆU (Tạo cùng thư mục với main.js)
- cookies.txt: Mỗi dòng chứa 1 Cookie của 1 tài khoản.
  (Cách lấy: F12 trên web DeltaHash -> Network -> F5 -> Tìm Header 'Cookie')
  "connect.sid=s%3AesgKlLOvZbn3qTbhfW4PYC3LKi6kE-PI.4StKIHOFJ680SGV83zSkSvbeQlBoqkgep0CKnvUjZCk; _ga_1CN7T7H5R3=GS2.1.s1776623804$o2$g1$t176623822$j42$l0$h0"
- proxy.txt: Mỗi dòng 1 Proxy định dạng http://user:pass@ip:port (Hoặc để trống nếu không dùng).
- user_agents.txt: Mỗi dòng 1 chuỗi User-Agent trình duyệt (Dùng để giả lập máy thật).
- license.txt: Dán Key bản quyền vào đây (Nếu chưa có, lúc chạy tool sẽ yêu cầu nhập).

3. CÁC TÍNH NĂNG TỰ ĐỘNG
- Tự động kiểm tra Proxy và IP.
- Tự động Login bằng Cookie.
- Tự động kích hoạt đào (Mining) và gửi nhịp đập (Heartbeat) mỗi 30 giây để nhận $DTH.

4. CÁCH CHẠY TOOL
- Mở CMD/Terminal tại thư mục tool và gõ lệnh:
  node main.js

LƯU Ý: 
- Nếu Tool báo lỗi Login, hãy lấy lại Cookie mới (Cookie thường hết hạn sau một thời gian).
- Tool chạy đa luồng giả, sẽ xử lý lần lượt từng tài khoản trong file cookies.txt.

Tham Gia NHóm tele : https://t.me/HVchannelss

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 1 Tháng 4u - 15u 6thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây

Donenat : https://huynhviet933.github.io/donate_viet_mmo/
