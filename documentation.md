Công nghệ: Ignite CLI, Cosmos SDK
Muốn tạo RWA network, base EVM, build với Cosmos SDK. Mục đích: Khách hàng muốn token hóa chứng khoán và bất động sản, đưa tài sản thực lên blockchain. Bắt buộc theo chuẩn ERC-1400, POS.

1. Người dùng tham gia vào việc mở rộng hệ sinh thái như chuyển nhượng, truyền tải, phát hành token và xác minh nút sẽ nhận được Almighty Token (AMT) dưới dạng token thưởng (Bất cứ khi nào STOC bị đốt, những người tham gia nắm giữ hơn 10.000 STOC sẽ nhận được AMT/Almight Token có thể được đổi lấy STOC theo một tỷ giá nhất định)
2. Có thể khai thác AMT bằng DApp không? (Ngay cả khi ai đó không liên tục hoạt động, giống như một trò chơi nhàn rỗi, AMT vẫn có thể được khai thác)
3. Nếu hệ thống phát hành RWA phải chỉ là POA, liệu có thể biến chuỗi công khai thành POS và chuỗi riêng tư thành POA và kết nối hai hệ thống này không?

4. Technical stuffs:
- Có 10 tỉ token mới, vậy sẽ setup như thế nào? (em đã tìm hiểu về config.yml, nhưng không rõ lắm ở phần chia tài sản).
- (Tokenomic) Summary 15% cho team & advisors, 10% cho liquidity, 10% cho IDO, etc, khi deploy chain và validator thì phải chia coin cho các node validator như thế nào? Khi init chain, save coin vào 1 ví admin hay chia cho nhiều ví? Khi transfer coin cho validator thì sẽ mất 1 ít gas, phần này minh sẽ mint thêm hay sử dụng coin ở đâu?
- Flow build chain (mainnet khác gì testnet), deploy chain, add validator
- Khi update chain thì làm các bước như thế nào?
- Phần staking cho user, lock token trong 1 thời gian, vậy phải setup như thế nào?
- Có module RWA (real world asset), vậy phải setup như thế nào?
