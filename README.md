# Viết Dapp thực hiện lấy balance của một địa chỉ ví

- Network: TomoChain
- RPC: https://rpc.tomochain.com
- ChainID: 88
- Symbol: TOMO
- Decimals: 18
- Scanner: https://tomoscan.io

# Mô tả ứng dụng:
- Ứng dụng bao gồm một textbox(1) để nhập địa chỉ ví, sau đó nhấn nút search sẽ lấy ra balance TOMO của địa chỉ ví đã nhập
- Thêm một textbox(2) nữa để nhập địa chỉ contract ERC20, sau đó lấy balance của token ERC20 vừa nhập của địa chỉ trong textbox1
- Balance tự động cập nhật nếu có thay đổi mà không cần nhấn lại vào nút search
- Ví dụ 1 địa chỉ ví: 0xfacE33fAdb3742b37dB75870e3F021Af34C31A81
- Ví dụ 1 địa chỉ token erc20: 0x8865280c31B8CBC7b96cE48Ad52C122E6D82806a
- Xem balance TOMO của địa chỉ ví qua ứng dụng scan: https://tomoscan.io/address/0xfacE33fAdb3742b37dB75870e3F021Af34C31A81
- Xem balance token erc20 của địa chỉ qua scan: https://tomoscan.io/token/0x8865280c31B8CBC7b96cE48Ad52C122E6D82806a?account=0xfacE33fAdb3742b37dB75870e3F021Af34C31A81

# Yêu cầu:
- Sử dụng ReactJS
- Không sử dụng API để lấy balance, mà phải sử dụng thư viện web3 bên trên, kết nối qua RPC

# Gợi ý:
- Sử dụng thư viện: https://web3js.readthedocs.io/en/v1.3.4/
