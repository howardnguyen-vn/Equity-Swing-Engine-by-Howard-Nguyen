Ý Tưởng Chính
Chỉ báo này tìm các mô hình giá trên cổ phiếu Việt Nam, rồi chia trạng thái thành 3 bước:
- FORMING: mô hình đang hình thành.
- ARMED: giá đã sát vùng phá vỡ, cần chú ý.
- FIRED: giá đã phá vỡ đủ điều kiện, có tín hiệu hành động.
Với cổ phiếu cơ sở Việt Nam, mặc định chỉ báo không tạo lệnh short. Tín hiệu giảm chỉ là risk_off, tức cảnh báo rủi ro hoặc cân nhắc giảm tỷ trọng.
Các Khối Cài Đặt
- Scanner Engine: điều chỉnh cách phát hiện swing/pivot.
Quan trọng nhất là Pivot Length. Số càng cao thì tín hiệu ít hơn nhưng sạch hơn. Với Daily cổ phiếu VN, mặc định 13 là hợp lý.
- Pattern Types: chọn loại mô hình muốn quét.
Có Double Top/Bottom, Vai Đầu Vai, Tam giác, Flag, Wedge. Người mới cứ bật hết, sau đó quan sát mô hình nào hợp với cổ phiếu mình hay giao dịch.
- Viet Nam Stock Market Layer: phần riêng cho thị trường Việt Nam.
- Có Trading Mode:
+ VN Cash: long only + risk alerts: mặc định, phù hợp cổ phiếu cơ sở.
+ Long signals only: chỉ hiện tín hiệu mua.
+ Allow shorts (derivatives only): chỉ dùng nếu áp dụng cho phái sinh hoặc thị trường cho short.
Phần này còn có lọc thanh khoản, gap đầu phiên, nến gần trần/sàn, và lọc theo VNINDEX.

Howard Nguyen Quality Layer: lớp lọc chất lượng.
Min Confluence là điểm tối thiểu, mặc định 6/10. Tín hiệu càng cao càng đáng chú ý. Nó xét xu hướng khung lớn, thị trường chung, volume, độ nhiễu, R:R và ATR.
Targets & Display: điều chỉnh phần hiển thị.
Khi bullish FIRED, chỉ báo vẽ ENTRY, SL, TP1, TP2. Khi bearish trong chế độ cổ phiếu cơ sở, nó chỉ vẽ RISK LEVEL.
Alerts: bật/tắt alert JSON khi có tín hiệu FIRED.
Cách Đọc Dashboard
PATTERN: mô hình đang được phát hiện.
PHASE: trạng thái hiện tại: FORMING, ARMED, FIRED.
FORMATION: phần trăm hoàn thiện mô hình.
NECKLINE: vùng giá quan trọng cần phá vỡ.
ENTRY / RISK LEVEL: điểm mua nếu bullish, hoặc vùng rủi ro nếu bearish.
TP1 / TP2: mục tiêu chốt lời, chỉ hiện với tín hiệu long hoặc khi bật short.
STOP: điểm dừng lỗ.
CONFLUENCE: điểm chất lượng từ 0 đến 10.
HTF / MARKET: xu hướng cổ phiếu khung lớn và VNINDEX.
VALUE / VOL: thanh khoản và volume hiện tại so với trung bình.
GAP / BAND: gap đầu phiên và biên độ trần/sàn.
Cách Sử Dụng Cho Người Mới
Mở chart cổ phiếu VN trên TradingView, ưu tiên khung 1D.
Thêm chỉ báo vào chart.
Để Trading Mode là VN Cash: long only + risk alerts.
Kiểm tra Market Index Symbol, mặc định là HOSE:VNINDEX.
Nếu TradingView hiển thị giá theo nghìn VND, đổi Price Multiplier for Value thành 1000.
Chỉ quan tâm tín hiệu khi PHASE = FIRED.
Ưu tiên tín hiệu có CONFLUENCE >= 6/10.
Với lệnh mua, nên thấy thêm: thị trường chung không quá xấu, volume breakout tốt, không phải nến gap quá lớn hoặc sát trần.
Nếu thấy bearish FIRED, không hiểu là lệnh short; hiểu là cảnh báo rủi ro.
Quy Tắc Đọc Tín Hiệu Đơn Giản
Bullish ARMED: cổ phiếu đang gần vùng breakout, cho vào watchlist.
Bullish FIRED: có thể xem xét điểm mua, nhưng vẫn cần kiểm tra thị trường chung và quản trị rủi ro.
Bearish ARMED: cổ phiếu đang gần vùng gãy hỗ trợ.
Bearish FIRED: cảnh báo giảm tỷ trọng, siết stop, hoặc tránh mua mới.
Lưu ý quan trọng: chỉ báo dùng pivot nên mô hình chỉ được xác nhận sau một số nến nhất định. Nó không phải công cụ “bắt đáy/bắt đỉnh tức thì”, mà phù hợp hơn để lọc setup swing Daily/Weekly có cấu trúc rõ.
