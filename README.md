# EZLITE-MASTERNODE
SCRIPT hỗ trợ cài đặt nhanh và quản lý MASTERNODE chạy trên Ubuntu 16.04 
---
Link ref VPS ( nếu các bạn cần thuê VPS thì hãy click link ủng hộ mình nhé )
<a href="https://www.vultr.com/?ref=6984190"><img src="https://www.vultr.com/media/banner_2.png" width="468" height="60"></a>
---
# Hướng dẫn cài đặt :
1. Tạo wallet trên PC local >> đặt password ví >> đợi đồng bộ xong ví
2. Chuyển coin từ sàn về ví local >> vào tab <bold> Receice </bold>  >>  New Address >> đặt 1 label bất kỳ cho address mới >> copy address đó lại
3. Sang  tab Send >> gửi vào label đó lượng coin đúng bằng MASTERNODE REQUIRED ( xem tại trang chủ , github, bitcointalk của coin đó )
4. Đợi Transaction đươc confirm ( thường biểu tượng dấu check ) 
5. Vào Debug Windows ( thường trong tab HELP ) 
  + Genkey : ``masternode genkey ``   >> Genkey dùng để làm file config và file masternode
  + TXHASH và TXID : ``masternode outputs ``  >> dãy hash dài là TXHASH , 0 hoặc 1 là TXID
6. Cài đặt script bên dưới lên VPS :
`` wget https://raw.githubusercontent.com/secrectvn/ezlite/master/install.sh && chmod +x install.sh && ./install.sh``
<p>
7. Sau khi cài đặt xong , bạn nên chọn Y để reboot lại vps
8. Sau đó gõ lệnh ``ezlite``  và thực hiện cài mới masternode mình muốn
9. Upload file wall.dat lên thư mực /root/masternode/tencoin
10. Start masternode lần đầu trong menu quản lý masternode 

### Chú ý code name sẽ là mã bên dưới , các bạn kiểm tra để chính xác nhé
Group Facebook : https://www.facebook.com/groups/168553500599564/


# DANH SÁCH COIN HỖ TRỢ

|Coin Name|Code Name|Logo|Website| Bitcointalk|
|---------|---------|----|-------|-----|
| HaveCoin |have |![have](/cryptos/have/logo.jpg)| http://www.havecoin.co/ | https://bitcointalk.org/index.php?topic=2336026.0 |
| Beetle Coin| beet |![beet](/cryptos/beet/logo.jpg)| https://beetlecoin.io/ | https://bitcointalk.org/index.php?topic=2961802.0 |
| Shekel |jew| ![jew](/cryptos/jew/logo.jpg)| http://shekel.io | https://bitcointalk.org/index.php?topic=2455628.0|
| Vantaur |vtar| ![vtar](/cryptos/vtar/logo.jpg)| http://vantaur.tk | https://bitcointalk.org/index.php?topic=2914598.0 |
| Vivo| vivo| ![vivo](/cryptos/vivo/logo.jpg)| https://www.vivocrypto.com | https://bitcointalk.org/index.php?topic=2110690.0 |
| GanjaCoin | mrja|![mrja](/cryptos/mrja/logo.jpg)|https://www.ganjacoinpro.com/ | https://bitcointalk.org/index.php?topic=2144531.0|
| Gainer | gnr| ![gnr](/cryptos/gnr/logo.jpg)| http://www.gainercoin.com | https://bitcointalk.org/index.php?topic=2746670|
| MNXC2 | mnxc| ![mnxc](/cryptos/mnxc/logo.jpg)| https://masternodexchange.com | https://bitcointalk.org/index.php?topic=2661428.0 |
| Relief |tgao| ![tgao](/cryptos/tgao/logo.jpg)| https://www.reliefproject.us/ | https://bitcointalk.org/index.php?topic=2243790.0 |
| FerrumCoin | frm |![frm](/cryptos/frm/logo.jpg) | https://www.ferrumcrypto.com/ | https://bitcointalk.org/index.php?topic=2971900.0 |


