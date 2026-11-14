# Market Rush — PeerJS + GitHub Pages

Kurulum gerekmez. `index.html` dosyasını GitHub deposuna yükleyip **Settings → Pages → Deploy from a branch → main / (root) → Save** seçin. Birkaç dakika sonra GitHub Pages bağlantısı açılır.

## Oynama

1. Burak oyunu açar, **Burak** ve **ODA OLUŞTUR** seçer.
2. İrem aynı URL'yi açar, **İrem** ve aynı oda koduyla **ODAYA KATIL** seçer.
3. WASD / ok tuşları veya ekrandaki yön tuşlarıyla hareket edilir.
4. Ürüne yaklaşın, **E / TOPLA** basın, aynı renkteki kategorik rafa yaklaşın, tekrar basın.
5. 1.000 ürün tamamlandığında sonraki markete geçilir. 5 market vardır.

## Önemli sınırlamalar

- Ürün kataloğu 11 gerçekçi süpermarket kategorisinde 1.000 adet benzersiz adlandırılmış ürün varyantından oluşur. Gerçek marka SKU veritabanı değildir. Her markette aynı katalog kullanılır; yerleşim değişir.
- Eşler arasındaki gerçek zamanlı bağlantı PeerJS Cloud ve WebRTC üzerinden kurulur; bazı NAT/ağ türlerinde TURN sunucusu olmadan çalışmayabilir.
- İlerleme **yalnızca oda sahibinin tarayıcısının localStorage alanına** kaydedilir. Farklı tarayıcıya geçmek, tarayıcı verilerini silmek veya oda sahibinin cihazını kaybetmek ilerlemeyi kaybettirebilir.
- Oda sahibi çevrimiçi değilken diğer oyuncu oynayamaz. Güvenli sunucu doğrulaması yoktur; oda kodunu özel tutun.
- 3D sahne prototip görselleri kullanır. 1.000 ürün sahnede basit geometrilerle çizilir; düşük performanslı cihazlarda yavaşlayabilir.
- Harici CDN'ler için internet gerekir.
- GitHub hesabına yükleme bu paket tarafından otomatik yapılmaz.