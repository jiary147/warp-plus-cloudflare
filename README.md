# Sınırsız warp+ Verisi Metodu

**Not: Bu betik benim tarafımdan yazılmamıştır. sadece tamamlanmış, türkçeleştirilmiş ve "tek başına çalıştırılabilirlik" eklenmiştir.** 😉

![](https://github.com/ALIILAPRO/warp-plus-cloudflare/blob/master/pic.png)

### Bu komut dosyasıyla warp+ hesabınızı süresiz olarak reşarj edebilirsiniz. 📱

### [?] warp+ nedir?
WARP +, daha yüksek hızlar elde etmek ve bağlantınızın İnternet'in uzun vadede şifrelenmesini sağlamak için Cloudflare’nin Argo olarak bilinen sanal özel omurgasını kullanır. [Daha Fazla Bilgi (İngilizce)](https://blog.cloudflare.com/announcing-warp-plus/)

### [?] betik nasıl kullanılır? *( windows, mac, linux )*
- Öncelikle Python'u sisteminize kurun. [Python 3.7+](https://www.python.org/downloads/)
- Modül isteklerini yükleyelim:
- cmd / terminale kopyalayın ve enterlayın: `pip install requests`
- [buradan](https://github.com/xorcan/warp-plus-cloudflare/archive/master.zip) projeyi indirin ve çıkartın (unzip)
- Ayıklanan dizinde bir cmd / terminal / kabuk açın
- Şu satırı girin: `python warp1.py`
- Komut dosyasını çalıştırın ve kullanın

### [?] tek başına çalışabilir betik (v2)
- normal bir kullanıcı için yukarıdaki gayet iyidir. bu sürümü yalnızca ne yaptığınızı biliyorsanız kullanın.
- teknik olarak hiçbir fark yok. ancak bu sürümdeki dosya tek komutta işinizi halleder.
- ayrıca size kimlik sormaz, rahatsız etmez. bilgi için programı başlatın.
- çalıştırmak için: `python warp2.py`

### [?] Androidde çalıştırmak

- [termux](https://play.google.com/store/apps/details?id=com.termux&hl=tr) uygulamasını yükleyin, açın ve şu komutu girin (kopyalayıp yapıştırabilirsiniz):
- `pkg install git pkg install python && pip install requests`
- ardından şu komutla giti kendi cihazınıza klonlayın (indirin): 
- `git clone https://github.com/xorcan/warp-plus-cloudflare.git`
- betiğin dizinini açın:
- `cd warp-plus-cloudflare`
- betiği çalıştını:
- `python warp{sürüm numarası}.py`


### [?] warp+ ID'sini nasıl alırım?

1. 1.1.1.1 uygulamasını açın.
2. Menü (üç nokta) işaretine tıklayın ☰
3. Gelişmiş (Advanced) > Tanılamalar (Diagonistics)
4. İstemci Yapılandırması (Client Configuration)'nın altındaki Kimlik (ID) > basılı tutun ve kopyalayın.

![](https://github.com/ALIILAPRO/warp-plus-cloudflare/blob/master/script.png)
