# Viết Dapp thực hiện lấy balance của một địa chỉ ví

- Network: TomoChain
- RPC: https://rpc.tomochain.com
- ChainID: 88
- Symbol: TOMO
- Decimals: 18
- Scanner: https://scan.tomochain.com

# Mô tả ứng dụng:
- Ứng dụng bao gồm một textbox để nhập địa chỉ ví, sau đó nhấn nút search sẽ lấy ra balance TOMO của địa chỉ ví đã nhập
- Balance tự động cập nhật nếu có thay đổi mà không cần nhấn lại vào nút search
- Ví dụ 1 địa chỉ ví: 0xfacE33fAdb3742b37dB75870e3F021Af34C31A81
- Xem balance của địa chỉ ví qua ứng dụng scan: https://scan.tomochain.com/address/0xfacE33fAdb3742b37dB75870e3F021Af34C31A81

# Yêu cầu:
- Sử dụng ReactJS, React hook
- Không sử dụng API để lấy balance, mà phải sử dụng thư viện web3 bên trên, kết nối qua RPC

# Gợi ý:
- Sử dụng thư viện: https://web3js.readthedocs.io/en/v1.3.4/
