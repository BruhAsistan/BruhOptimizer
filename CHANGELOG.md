## [17.3] - 2025-12-12
- Sürüm bilgisi 17.3’e güncellendi; güncel exe ile sol üstte doğru sürüm gösteriliyor.
- Güncelleme denetimi kendi repo (BruhOptimizer) version.txt ve CHANGELOG.md adreslerine çekildi.
- Windows 11’de sol menü başlığı artık “Windows 11” (Win10’da “Windows 10”) olarak görünüyor.
- “Görev çubuğundaki hava durumunu gizle” togglesında yetki hataları yakalanıyor; uyarı verilip toggle geri alınıyor (çökme önlendi). 


## [17.0] - 2025-12-04
- Yeni: Açılışta sistem durumunu okuyup ayarları otomatik senkronize ediyor (registry/hizmet tabanlı).
- Yeni: Güncelleme denetimi GitHub’daki `version.txt` ve `Optimizer.exe` üzerinden; indirme sonrası eski exe otomatik kapanıp yenisi başlıyor.
- Yeni: Güncelleme indirilirken hem raw (main) hem de releases/latest adresleri yedek (fallback) olarak deneniyor.
- Değişti: Dil seçenekleri sadeleştirildi; yalnızca Türkçe ve İngilizce kaldı.
- Değişti: Başlangıç, Ortak Uygulamalar, Temizleyici, Pinger ve Hosts sekmeleri ile ilgili ikonlar kaldırıldı.
- Değişti: Seçenekler’deki Discord ve SSS (FAQ) linkleri kullanıcı deposu adresine göre güncellendi; gereksiz destek/bağış linkleri gizlendi.
- Düzeltildi: Güncelleme ve değişiklik günlüğü (changelog) isteklerinde görülen bazı 404 hatalarını azaltmak için TLS 1.2 kullanımı ve hata mesajları iyileştirildi.
- Düzeltildi: Sağ alt ikon/görsel hizalamaları elden geçirildi; görünmeyen ikonlar kaynakları korunarak yeniden konumlandırıldı.

---

## [16.7] - 2024-08-18
- Yeni: Edge ve Chrome telemetri devre dışı bırakma seçenekleri artık Manifest v2 desteğini de kapsıyor.
- Yeni: Kayıt defteri (Registry) periyodik yedeklemelerini etkinleştirme seçeneği eklendi.
- Düzeltme: Çeşitli arayüz (UI) hataları giderildi.

## [16.6] - 2024-07-06
- Yeni: Integrator içinde Sistem Değişkenleri (System Variables) düzenleyici eklendi.
- Yeni: Copilot + Recall özelliğini devre dışı bırakma seçeneği eklendi.
- Yeni: Phone Link önerilerini devre dışı bırakma seçeneği eklendi.
- Yeni: Microsoft Hizmet reklamlarını “öneri” olarak gösteren alanları devre dışı bırakma seçeneği eklendi.
- Yeni: Endonezce ve Hırvatça dil desteği eklendi.
- Düzeltme: Yanlış pozitifler sebebiyle Zararlı Yazılım Kaldırma aracı tamamen hariç tutuldu.
- İyileştirme: Yerelleştirme (çeviri) güncellemeleri.
- İyileştirme: Görsel değişiklikler.

## [16.5] - 2024-05-03
- Yeni: Windows genelinde UTC zamanı etkinleştirme seçeneği.
- Yeni: Windows 10/11’de Modern Standby özelliğini devre dışı bırakma.
- Yeni: Görev çubuğundan Arama ve Hava Durumu simgelerini gizleme.
- Yeni: Haberler ve İlgi Alanları (News & Interests) özelliğini devre dışı bırakma.
- Yeni: Görev çubuğunda tüm bildirim simgelerini gösterme.
- Yeni: Menü gecikmesini kaldırma seçeneği.
- Yeni: Vietnamca ve Urduca dil desteği.
- Yeni: CoPilot AI devre dışı bırakma artık Edge için de uygulanıyor.
- İyileştirme: Yerelleştirme güncellemeleri.
- İyileştirme: Birçok kalite iyileştirmesi.
- Düzeltme: Başlangıç (Startup) öğelerinde sıralama sırasında silinme hatası (#489).

## [16.4] - 2023-12-29
- Yeni: Seçenekler (Options) bölümüne SSS (FAQ) bağlantısı eklendi.
- Yeni: Kod yeniden düzenlemesi (refactoring) ile çeşitli performans iyileştirmeleri.
- Düzeltme: Güncelleme kontrolü sırasında nadiren görülen hata (#444).
- Düzeltme: SmartScreen artık doğru şekilde sıfırlanıyor (#453).
- Düzeltme: Uygulamalar indirme klasörü varsayılan olarak boş ayarlandı, böylece olası sorunlar önlendi.
- Düzeltme: Uygulama akışlarını (app feeds) çekerken nadiren görülen hata (#450).

## [16.3] - 2023-12-22
- Yeni: Başlangıçta güncelleme denetimi seçeneği (#441, #423).
- Yeni: Klasik Windows Gezginini Geri Yükle (Restore Classic Windows Explorer) bölümüne Hava Durumu ve Arama’yı gizleme seçenekleri eklendi (#447).
- Düzeltme: Tüm kullanıcılar için web aramasını devre dışı bırakma (#427).
- Düzeltme: İnce ayar (tweak) seçenekleri artık dinamik olarak doğru şekilde devre dışı bırakılıyor (#431).
- Düzeltme: Otomatik Güncellemeleri Devre Dışı Bırak, artık Mağaza uygulamasının yükleme/güncellemesini bozmuyor.
- Düzeltme: DPI ölçeklendirme sayacı için yedek mekanizma eklendi.

## [16.2] - 2023-10-28
- Geri adım: VirusTotal’da çok fazla yanlış pozitif sebebiyle ‘Microsoft Edge’i Kaldır’ seçeneği kaldırıldı.

## [16.1] - 2023-10-21
- Düzeltme: ‘İlkeleri güçlendir (Reinforce policies)’ ile ilgili sorunlar çözüldü (#401, #402).
- Yeni: Gelişmiş Ayarlar (Advanced Tweaks) altında ‘Microsoft Edge’i Tamamen Kaldır’ seçeneği eklendi (geri alınamaz!).
- Yeni: “Performansı Optimize Et (Optimize Performance)” ve “Gizliliği Artır (Enhance Privacy)” için seçmeli (selective) ince ayarlar eklendi (#393, #374).

## [16.0] - 2023-10-14
- Düzeltme: ‘İlkeleri güçlendir (Reinforce policies)’ çökme sorunu giderildi (#400).

## [15.9] - 2023-10-14
- Yeni: Windows 11 için CoPilot AI devre dışı bırakma.
- Yeni: Bulgarca diline tam çeviri eklendi.
- Yeni: Seçenekler’deki ‘İlkeleri güçlendir’ (Reinforce policies), etkin olan tüm ince ayarları yeniden uygular (#389).
- Düzeltme: Yerelleştirilmiş Windows sürümlerinde yaşanan çökme hatası (#383).
- Düzeltme: Çeşitli UI hataları düzeltildi.
- İyileştirme: Görseller ve varlıklar optimize edildi.
- İyileştirme: Başlangıç öğeleri algılama iyileştirildi.

## [15.8] - 2023-08-26
- Yeni: Nepali diline tam çeviri eklendi (katkı: chapagetti).
- Yeni: Pinger içinde özel DNS belirleme, ayrıca şablon üzerinden ayarlama desteği.
- Yeni: Hangi araçların yükleneceğini kontrol eden dahili ayarlar.
- Düzeltme: Çeşitli UI sorunları ve yerelleştirme güncellemeleri.

## [15.7] - 2023-08-19
- Yeni: Integrator içinde Windows varsayılan yazı tipini değiştirme (#358).
- Yeni: Şablon motoru artık Windows Server 2008 ve sonrası sürümlerde çalışıyor.
- Düzeltme: UWP uygulamalarını yüklerken nadir görülen çökme.
- İyileştirme: Sekme titremesi (tab glitching) sorunu giderildi (#376).
- İyileştirme: Başlat menüsü reklamlarını devre dışı bırakma ve Mağaza güncellemelerini devre dışı bırakma.
- İyileştirme: Hosts düzenleme ve loglama ile ilgili şablon motoru değişiklikleri.

## [15.6] - 2023-07-22
- Düzeltme: UWP uygulamalarını yüklerken yaşanan çökme (#369, #370).

## [15.5] - 2023-07-22
- Yeni: Farsça (Persian) diline tam çeviri eklendi (katkı: https://github.com/MjavadH - MjavadH).
- Yeni: Uygulamalar > İnternet bölümüne RustDesk eklendi.
- Yeni: Yeniden başlatma öncesi onay penceresi eklendi (#343).
- Yeni: Hosts dosyasında WWW CNAME öneki ekleme seçeneği.
- İyileştirme: Çeşitli yerelleştirme güncellemeleri.
- İyileştirme: Hata kayıt sistemi artık yakalanmamış (unhandled) istisnaları da destekliyor.
- İyileştirme: Düşük çözünürlüklü ekranlarda UI geliştirmeleri.
- İyileştirme: Varsayılan uygulama indirme klasörü, kullanıcının İndirilenler klasörüne ayarlandı.

## [15.4] - 2023-06-14
- Yeni: Windows 10/11’de Klasik Fotoğraf Görüntüleyiciyi geri yükleme (#342).
- Düzeltme: Çeşitli UI hataları giderildi.

## [15.3] - 2023-05-18
- Yeni: Yeniden kullanılabilir şablonlarla otomasyon motoru (bkz. https://github.com/hellzerg/optimizer/blob/master/AUTOMATION.md).
- Düzeltme: Çeşitli yerelleştirme güncellemeleri.
- Düzeltme: Cleaner’da Mozilla Firefox seçilirken nadir görülen hata.
- Düzeltme: UI ölçeklendirmesinde iyileştirmeler.

## [15.2] - 2023-05-11
- Yeni: svchost işlem bölme (process splitting) mekanizmasını devre dışı bırakma veya sıfırlama.
- Düzeltme: UWP uygulamaları yüklenirken nadir görülen çökme.
- Düzeltme: UWP uygulamalarının Windows 8/8.1’de doğru şekilde yüklenmesi.
- Düzeltme: Çeşitli yerelleştirme güncellemeleri.

## [15.1] - 2023-04-23
- Düzeltme: Edge Discover devre dışı bırakma artık doğru çalışıyor.
- İyileştirme: SmartScreen ve Visual Studio Telemetry devre dışı bırakma.

## [15.0] - 2023-04-16
- Yeni: Ek ince ayarlar ile Gelişmiş sekmesi. Bu sekmeyi kullanmak için `/unsafe` parametresini kullanın.
- Yeni: Gelişmiş’te HPET devre dışı bırakma.
- Yeni: Gelişmiş’te Ayrıntılı Oturum Açma (Verbose Login) etkinleştirme.
- Yeni: Edge Telemetry devre dışı bırakma.
- Yeni: Edge Discover çubuğunu devre dışı bırakma.
- Yeni: Küçük görsel değişiklikler.
- Düzeltme: Bazı durumlarda Hosts sekmesinin yüklenmemesi.
- Düzeltme: Çeşitli yerelleştirme güncellemeleri.
- Kaldırıldı: Microsoft tarafından kaldırıldığı için Windows 11’de Klasik Şerit (Classic Ribbon).
- Kaldırıldı: Microsoft tarafından kaldırıldığı için Windows 11’de Görev Çubuğu Boyutu ayarı.
- Kaldırıldı: Optimizer Insights telemetri servisi.

## [14.9] - 2023-02-18
- Yeni: OneDrive kaldırma seçeneği yalnızca GÜVENSİZ MOD’DA (UNSAFE MODE) görünür, sebebi malum...
- Yeni: Optimizer Insights, gizliliğe saygılı şekilde, uygulamanın ürettiği her hatayı ileri analiz için toplar.
- Yeni: Elbette, Optimizer Insights’ı Seçenekler bölümünden devre dışı bırakabilirsiniz.
- Yeni: Japoncaya tam çeviri (katkı: Yamada Hayao - https://github.com/Hayao0819) (#286).
- İyileştirme: Küçük kod düzenlemeleri.

## [14.8] - 2023-01-07
- Yeni: Daha iyi performans ve destek için .NET Framework 4.8’e geçildi.
- Yeni: Tüm UWP uygulamalarını geri yükle seçeneği eklendi.
- İyileştirme: Komut satırı işleyicisi (command-line processor) yeniden düzenlendi.
- Düzeltme: UWP kaldırma onay mesajı düzeltildi (#281).

## [14.7] - 2022-12-24
- Düzeltme: Tema rengi hatası, açılışta çökme sebebi olmaktan çıkarıldı.

## [14.6] - 2022-12-17
- Yeni: Microsoft Store güncellemelerini devre dışı bırakma.
- Düzeltme: Otomatik/manuel güncellemeler tekrar düzgün çalışıyor.
- Düzeltme: NTFS Zaman Damgası devre dışı bırakma, yeniden başlatma sonrası korunuyor.
- Kaldırıldı: Özellik güncellemelerini (Feature Updates) devre dışı bırakma seçeneği.

## [14.5] - 2022-11-26
- Yeni: Ukraynaca diline tam çeviri (katkı: Kirill Ermakov - https://github.com/kirill0ermakov) (#261).
- Yeni: Genel sekmesine Arama servisini devre dışı bırakma eklendi (#257).
- Düzeltme: Klasik Dosya Gezgini sıfırlanırken Hava Durumu’nun tekrar etkinleşmemesi sorunu (#263).
- Düzeltme: Hosts Düzenleyicisi, artık alan adının başına www öneki eklemiyor (#259).
- İyileştirme: Varlık temizliği, dosya boyutu azaltıldı (#260).

## [14.4] - 2022-11-05
- Düzeltme: Game Bar’ı devre dışı bırakmak, artık Oyun Modu’nu kapatmıyor.
- Düzeltme: Explorer için Klasik Şerit’i sıfırlama, Windows 11’de düzgün çalışıyor.

## [14.3] - 2022-10-26
- Yeni: Windows 11 için Sanallaştırma tabanlı güvenliği (VBS) devre dışı bırakma.
- Yeni: Her anahtar için daha sade kategori yapısı.
- Yeni: Tarafsızlık için gri tonlu uygulama ikonu.
- Düzeltme: Sekme başlıklarında ölçeklendirme problemi.

## [14.2] - 2022-10-21
- Düzeltme: Ana sekmeler için doğru DPI ölçeklendirmesi (#236).
- Düzeltme: Hollandaca dili kaydedilip geri yüklenmiyordu, düzeltildi.
- İyileştirme: Chrome Telemetry, Enhance Privacy ve Optimize Performance seçenekleri geliştirildi.
- Kaldırıldı: Tepsi menüsündeki ağ izleme (network monitoring).

## [14.1] - 2022-10-18
- Yeni: Tüm renk spektrumunu destekleyen tema motoru (katkı: cat - https://github.com/vadiscode).
- Yeni: Universal bölümünde NVIDIA Telemetry devre dışı bırakma.
- Yeni: Seçenekler’de Windows ile başlatma seçeneği (yeterli izinle çalışır).
- Düzeltme: İnternet olmadığında uygulamanın çökmesi.
- Düzeltme: Çeviri sorunları.
- İyileştirme: Enhance Privacy ve Superfetch seçenekleri.

## [14.0] - 2022-09-24
- Yeni: Hollandaca diline tam çeviri (katkı: svanlaere - https://github.com/svanlaere).
- Düzeltme: Snap Assist çalışmıyordu, düzeltildi.
- Düzeltme: Yeniden Başlat düğmesi çökme sorunu.
- Düzeltme: UWP uygulama resim hatası.
- Düzeltme: Çince çeviri.
- İyileştirme: Yapılandırmayı Sıfırla, ismi “Onar (Repair)” olarak değiştirildi; çünkü bu, sıfırlama değil otomatik onarım mekanizması.

## [13.9] - 2022-08-21
- Düzeltme: Her bir anahtar için yardım mesajları artık ayrı bir panelde gösteriliyor.
- Düzeltme: Uygulama içinden yeniden başlatma, ayarları kaydetmeme sorununu gideriyor.

## [13.8] - 2022-08-20
- Yeni: Universal bölümünde Hazırda Bekletmeyi (Hibernate) devre dışı bırakma.
- Yeni: Universal bölümünde NTFS zaman damgasını devre dışı bırakma.
- Yeni: Universal bölümünde SMBv1 & SMBv2 protokollerini devre dışı bırakma.
- Yeni: UWP Uygulama listesindeki simgeleri gösterme (#213).
- Yeni: Gerekli durumlarda Yeniden Başlat uyarısı gösterme.
- Yeni: “Performans İyileştirmelerini Etkinleştir” adı, “Performansı Optimize Et” olarak değiştirildi.
- Yeni: Splash görseli güncellendi.
- İyileştirme: Performans iyileştirmelerinde bellek dökümü boyutunu azaltan ince ayar geliştirildi.
- Düzeltme: Telemetry Hizmetlerini devre dışı bırakmak artık pil istatistiklerinden sorumlu WdiSystemHost servisini durdurmuyor (#214).

## [13.7] - 2022-08-05
- Yeni: ```/disablehpet``` ve ```/enablehpet``` parametreleri ile HPET’i devre dışı bırakma/açma.
- Yeni: ```/addstartup``` parametresi ile Optimizer’ı başlangıçta çalıştırma (#206).
- Düzeltme: Telemetry Hizmetlerini devre dışı bırakmak artık ağ kullanımından sorumlu Diagnostics Policy servisinin (DPS) devre dışı kalmasına yol açmıyor (#212).
- Düzeltme: Uygulamalar (Apps) sekmesinde yazılım listesi için doğru DPI ölçeklendirmesi (#193).
- İyileştirme: Enhance Privacy artık Phone Link’i de devre dışı bırakıyor.

## [13.6] - 2022-06-12
- Yeni: Romence diline tam çeviri (katkı: BeamingNG - https://github.com/BeamingNG).
- Yeni: DPI farkındalığı (DPI awareness) desteği.
- İyileştirme: Enhance Privacy ince ayarını doğru şekilde sıfırlama.

## [13.5] - 2022-06-05
- Yeni: Macarcaya tam çeviri (katkı: Zan).
- Düzeltme: TPM kontrolünü devre dışı bırakma çalışmıyordu.
- Düzeltme: Cloud Clipboard (Bulut Panosu) için düzgün sıfırlama.

## [13.4] - 2022-05-14
- Düzeltme: Ağ çevrimdışıyken yüklerken yaşanan çökme.

## [13.3] - 2022-05-10
- Yeni: Kürtçe diline tam çeviri (katkı: Parwar Andam).

## [13.2] - 2022-05-08
- Yeni: Cleaner içinde Brave tarayıcı desteği (#176).
- Yeni: Dosya kilit tutan süreçleri bulma ve bu süreçleri öldürerek kilidi kaldırma.
- Düzeltme: Kaldırılan UWP uygulamalarının listede kalmaya devam etmesi sorunu (#129).
- Düzeltme: 'Dosyalarda Kompakt Modu Etkinleştir' ayarının mevcut durumu yansıtmaması sorunu.

## [13.1] - 2022-05-07
- Yeni: Pinger ile DNS sunucularını hızlıca değiştirme (Cloudflare, OpenDNS, Quad9, Google, Alternate, Adguard, Cleanbrowsing).
- Düzeltme: Cleaner’ın alt klasörleri boşaltmaması ile ilgili nadir bir sorun.
- Düzeltme: Enhance Privacy anahtarına basıldığında yanıt vermeme sorunu.
- Düzeltme: Tüm pencereyi taşırken FPS düşüşleri (#175).

## [13.0] - 2022-05-04
- Yeni: Windows 11 için Dosyalar’da Kompakt Modu etkinleştirme (dosyalar arası fazladan boşluğu kaldırır).
- Yeni: Cleaner artık tercihlerinize göre tahmini boyut hesaplıyor.
- Yeni: Yeni bir güncelleme penceresi.
- Düzeltme: ```/disablehibernate``` ve ```/enablehibernate``` parametrelerini kullanırken yapılandırma bulunamadı hatası.

## [12.9] - 2022-05-03
- Yeni: Defender’ı otomatik etkinleştirme (```/restart=enabledefender```).
- Yeni: Hazırda bekletme (hibernation) özelliğini komut satırından açma/kapama (```/disablehibernate``` & ```/enablehibernate```).
- Yeni: Anahtarlar için erişilebilirlik desteği (#150).
- Düzeltme: Sistem Geri Yükleme’yi devre dışı bırakmayı seçerken uyarı gösterimi.

## [12.8] - 2022-05-02
- Yeni: Oyun Modunu etkinleştirme (donanım hızlandırmalı GPU zamanlaması dahil).
- Yeni: Ortak Uygulamalar’a Brave tarayıcı eklendi.
- Yeni: Defender’ı otomatik devre dışı bırakma (```/restart=disabledefender```).
- Düzeltme: OneDrive kaldırma seçeneğini seçerken uyarı gösteriliyor.
- Düzeltme: Performans İyileştirmeleri, artık tepsi simgelerini gruplayan oku (tray grouping) devre dışı bırakmıyor.
- Düzeltme: Neredeyse tüm dillerde çeviri düzeltmeleri.
- İyileştirme: Biraz daha hızlı yükleme süresi.
- Kaldırıldı: Bildirim/Eylem Merkezi’ni devre dışı bırakma.

## [12.7] - 2022-04-03
- Yeni: Arapça diline tam çeviri (katkı: https://github.com/MesterPerfect - MesterPerfect).

## [12.6] - 2022-04-03
- Yeni: Cleaner aracı yeniden tasarlandı.
- Düzeltme: Klasik Şerit’i etkinleştiren kayıt defteri anahtarı düzeltildi.
- Düzeltme: Çeviri sorunları.

## [12.5] - 2022-04-02
- Yeni: Lehçe diline tam çeviri (katkı: https://github.com/factuall - Adrian Nieściur).

## [12.4] - 2022-03-29
- Yeni: Korece diline tam çeviri (katkı: https://github.com/VenusGirl - VenusGirl).
- Yeni: Newtonsoft.Json 12.0.2’den 13.0.1’e güncellendi.
- Düzeltme: Tüm desteklenen dillerde çeviri eklemeleri ve düzeltmeleri.
- İyileştirme: Performans İyileştirmeleri.

## [12.3] - 2022-03-27
- Düzeltme: İtalyanca çevirisi.
- Düzeltme: DNS önbelleğini temizleme (Flush DNS) artık onay gerektiriyor.
- Düzeltme: Taiwan bayrağı yerine yanlışlıkla Çin bayrağı gösterilmesi düzeltildi.
- Kaldırıldı: Çeşitli hatalar sebebiyle Hosts içindeki hazır AdBlock listeleri.

## [12.2] - 2022-03-26
- Düzeltme: Almanca dil seçiliyken yükleme esnasında çökme.

## [12.1] - 2022-03-26
- Yeni: Tayvanca diline tam çeviri (katkı: https://github.com/H3XDaemon - H3XDaemon).
- Yeni: Common Apps beslemesine ShareX eklendi.
- İyileştirme: Almanca ve İtalyanca çeviri sorunları giderildi.
- Kaldırıldı: Xbox Live anahtarından Donanım hızlandırmalı GPU zamanlaması.

## [12.0] - 2022-03-06
- Yeni: Çekçe diline tam çeviri (katkı: https://github.com/tomlonghorn - Tom Longhorn).

## [11.9] - 2022-02-23
- Düzeltme: Windows 11’de izin sorunları (#97).

## [11.8] - 2022-02-21
- Yeni: Komut satırından normal ve minimal güvenli modda yeniden başlatma.
- Düzeltme: Ağ izleme (network monitoring) başlangıç süresinin hızlandırılması.
- Düzeltme: Her dil için ana pencere boyutunu maksimum görünürlük için yeniden boyutlandırma.
- Küçük görsel değişiklikler.

## [11.7] - 2022-02-10
- Düzeltme: Ağ izleme desteklenmediği durumlarda yükleme sırasında takılma (#93, #95).

## [11.6] - 2022-02-08
- Yeni: Google Chrome telemetri ve yazılım raporlama aracını devre dışı bırakma.
- Yeni: Mozilla Firefox telemetri ve veri toplama servisini devre dışı bırakma.
- Yeni: Visual Studio telemetri, geri bildirim ve kolektör servisini devre dışı bırakma.
- İyileştirme: Office telemetri ayarları.

## [11.5] - 2022-01-31
- Düzeltme: Windows 7’de CPU tespit ederken çökme (#90).

## [11.4] - 2022-01-30
- Yeni: Donanım özelliklerini görüntüleme aracı.
- Yeni: Hızlı Erişim menüsünde (Quick Access) ağ hızı izleme (etkinleştirildiyse).

## [11.3] - 2022-01-29
- Telemetri servisleri, Gizlilik geliştirmeleri vb. bir çok alanda kalite iyileştirmeleri.
- Görsel değişiklikler.

## [11.2] - 2022-01-28
- Yeni: Arayüz, göz yormayacak şekilde kısmen yeniden tasarlandı.
- Birkaç hata düzeltmesi.

## [11.1] - 2022-01-23
- Yeni: Cleaner’da büyük tarayıcı desteği (önbellek, çerezler, geçmiş, oturum, şifre temizleme).

## [11.0] - 2022-01-15
- İyileştirme: Tüm desteklenen dillerde çeviri düzeltmeleri.

## [10.9] - 2021-12-12
- Yeni: Çince diline tam çeviri (katkı: https://github.com/btwise - btwise).

## [10.8] - 2021-12-05
- Yeni: Integrator’da ‘Komut İstemi ile Aç (Open with CMD)’ seçeneği ekleme/silme (#73).
- Düzeltme: Meet ikonunu düzgün devre dışı bırakma.

## [10.7] - 2021-11-23
- Yeni: ‘Meet Now’ ikonunu devre dışı bırakma (Klasik Dosya Gezgini Geri Yükle bölümünde).
- Yeni: Başlat Menüsü Reklamlarını Devre Dışı Bırak alanına kilit ekranı önerilerini devre dışı bırakma eklendi.
- Düzeltme: Portekizce çevirisi düzeltildi.
- Küçük hata düzeltmeleri.

## [10.6] - 2021-11-16
- Yeni: İtalyanca diline tam çeviri (katkı: https://github.com/Ziocash - Ziocash).
- Yeni: Dosya Gezgini’nde Dosya Geçmişi’ni devre dışı bırakma (Restore Classic File Explorer içinde).
- Yeni: Daha yumuşak açılış için yükleme animasyonu.

## [10.5] - 2021-11-14
- Yeni: Performans İyileştirmeleri içinde “Burada Komut İstemi Aç (Open Command Prompt here)” seçeneği.
- Yeni: Klasik Dosya Gezgini Geri Yükle içinde görev çubuğunda Haberler ve Hava Durumu’nu devre dışı bırakma.

## [10.4] - 2021-10-29
- Düzeltme: İspanyolca dil seçiliyken çökme.

## [10.3] - 2021-10-10
- İyileştirme: TPM Kontrolünü devre dışı bırakma (hem 2.0, hem 1.2, hem de RAM kontrolü).

## [10.2] - 2021-10-07
- Yeni: Optimizer artık tek örnek (single-instance) modunda çalışıyor.
- İyileştirme: Temizlemeden önce dosyaları önizleme ve seçme.
- İyileştirme: Fransızca çeviri.

## [10.1] - 2021-10-06
- Yeni: Windows 11 ile tamamen uyumlu (sessiz yapılandırma desteği ile).
- Yeni: Görev çubuğunu sola hizalama.
- Yeni: Snap Assist, Widget’lar ve Sohbet’i devre dışı bırakma.
- Yeni: Daha küçük görev çubuğu boyutu.
- Yeni: Dosya Gezgini’nde Klasik Şerit’i geri yükleme.
- Yeni: Klasik sağ tık menüsünü geri yükleme (Daha Fazla Seçenek Göster yok).
- Yeni: TPM 2.0 denetimlerini devre dışı bırakma, Windows 11’e yükseltmeye izin verir.
- Yeni: Tek örnek desteği.
- İyileştirme: Windows Update’ten sürücüleri hariç tutma.

## [10.0] - 2021-09-14
- Kod temizliği.
- Küçük UI değişiklikleri.

## [9.9] - 2021-08-23
- Yeni: Fransızcaya tam çeviri (katkı: https://github.com/RAFF47 - RAFF).

## [9.8] - 2021-08-04
- Yeni: Windows Defender’ı GÜVENLİ MODDA tamamen devre dışı bırakma – Optimizer.exe /disabledefender (Windows 10 1903 ve sonrası için bkz. Microsoft dokümanı).
- Yeni: Pinger içinde Cloudflare DNS yardımcısı.
- Yeni: Hata kaydında sistem detayları.

## [9.7] - 2021-08-02
- Yeni: Portekizceye tam çeviri (katkı: https://github.com/cassiompf - Cassio).

## [9.6] - 2021-07-24
- Yeni: İspanyolcaya tam çeviri (katkı: https://github.com/danielcshn - danielcshn).

## [9.5] - 2021-07-15
- Düzeltme: İnternet bağlantısı yokken çalıştırıldığında çökme.
- İyileştirme: Başlangıç öğeleri artık işaretlenebiliyor.

## [9.4] - 2021-07-14
- Yeni: Uygulama artık biraz daha hızlı açılıyor.
- Yeni: Enhance Privacy, Windows 10 Home sürümünde Grup İlkesi Düzenleyicisi’ni (gpedit.msc) etkinleştirmeye çalışıyor.
- İyileştirme: DNS önbelleği temizleme (Flush DNS).
- İyileştirme: Gizlilik ayarları (Cloud Search, Cihazımı Bul, Zaman Çizelgesi’ni devre dışı bırakır).
- İyileştirme: Defender ve Xbox ince ayarları.

## [9.3] - 2021-06-29
- Yeni: Almancaya tam çeviri (katkı: https://github.com/theflamehd - theflamehd).

## [9.2] - 2021-06-28
- Düzeltme: Yazım Denetimini devre dışı bırakmak artık kalem desteğini devre dışı bırakmıyor (bunu artık Disable Windows Ink yapıyor).
- Düzeltme: Besleme hatası etiketinin yanlış yerde görünmesi.

## [9.1] - 2021-06-26
- Uygulama boyutu ciddi oranda küçültüldü (~1.4 MB).
- Bellek yönetiminde iyileştirmeler (~110 MB yerine ~60 MB).
- Ortak Uygulamalar yeniden tasarlandı: Kategoriler ve tam dinamik uygulama yükleme.
- Küçük hata düzeltmeleri.

## [9.0] - 2021-06-24
- Yeni uygulamalar eklendi:
  .NET Framework 4.8,
  Java 8 JDK,
  Python 3 & 2,
  K-Lite Codec Pack Mega,
  VS Codium,
  Balena Etcher.
- Küçük hata düzeltmeleri.

## [8.9] - 2021-06-17
- Yeni: Yüklü .NET Framework sürümünü algılama.
- Yeni: Türkçeye tam çeviri (katkı: https://github.com/Kheasyque - Kheasyque) (#47).
- Düzeltme: Pinger, IPv6 dönerken çalışmıyordu; artık yalnızca IPv4 ping atıyor.

## [8.8] - 2021-06-07
- İlk çalıştırmada dil seçme özelliği.

## [8.7] - 2021-06-06
- Düzeltme: "Enhance Privacy" uygulanırken çökme.

## [8.6] - 2021-06-06
- Performans, gizlilik ve telemetri alanında birçok iyileştirme.

## [8.5] - 2021-06-05
- Yeni: Yunancaya tam çeviri (katkı: aplenaki).
- Rusça yerelleştirmede düzeltmeler.

## [8.4] - 2021-06-02
- Yeni: Rusçaya tam çeviri (katkı: https://github.com/mrkaban - mrkaban) (#5).
- Düzeltme: Bazı ayarların kaydedilmemesi sorunu (#38, #36).
- Düzeltme: Otomatik Güncellemeleri ve Defender’ı devre dışı bırakma sıfırlamasında iyileştirmeler (#42).
- Kaldırıldı: Edge indirme klasörünü değiştirme (eskidi).

## [8.3] - 2021-05-31
- Düzeltme: Hızlı Erişim menüsü etkinken güncelleme sırasında uygulamadan çıkmama sorunu.

## [8.2] - 2021-05-31
- Yeni: Sorun gidermek için "/reset" parametresi eklendi.
- İyileştirme: Otomatik Güncellemeleri ve Defender’ı etkinleştirme daha iyi hale getirildi.

## [8.1] - 2021-05-31
- Düzeltme: Pinger’ın bazen çalışmaması.

## [8.0] - 2021-05-30
- Yeni: Başlangıç öğelerini yedekleme ve geri yükleme.
- İyileştirme: Performans ayarları.
- İyileştirme: Daha iyi yapılandırma yönetimi.
- Düzeltme: Eksik uygulama indirme yolu tespiti.

## [7.9] - 2021-05-27
- Düzeltme: Kayıt defteri anahtar izni reddedildiğinde çökme (#37).

## [7.8] - 2021-04-17
- Düzeltme: Başlangıç klasörleri eksik olduğunda çökme.
- Başlangıç artık komut dosyalarını (batch) algılayabiliyor.

## [7.7] - 2021-04-15
- Düzeltme: Yerelleştirme sebebiyle yaşanan çökmeler.

## [7.6] - 2021-04-12
- Yeni: Yardım ipuçlarını göster/gizle seçeneği.
- UI parlatma (polishing).

## [7.5] - 2021-04-12
- Yeni: Her anahtarın üzerine gelince açıklamasını gösterme.
- İyileştirme: Özellik Güncellemelerini Devre Dışı Bırak.

## [7.4] - 2021-04-11
- İyileştirme: SmartScreen devre dışı bırakma.
- İyileştirme: Ortak Uygulamalar’da daha iyi UI ölçeklendirmesi.

## [7.3] - 2021-04-11
- Yeni: Pinger içinde DNS önbelleğini temizleme (Flush DNS).
- Düzeltme: Çevrimdışıyken bazı sekmelerin çalışmaması.
- Windows 10 gizlilik ayarlarında çeşitli iyileştirmeler.
- Gereksiz zamanlayıcılar kaldırıldı.

## [7.2] - 2021-04-10
- Lisanslar (LICENSES) artık Seçenekler içinde görülebiliyor.
- Açılışta güncelleme denetimi.

## [7.1] - 2021-04-10
- Yeni: Pinger, hızlı ping atma ve SHODAN.io araması yapabiliyor.
- Yeni: Hızlı Erişim menüsü – Seçenekler’den etkinleştirin.
- Düzeltme: SystemResponsiveness varsayılanı 14’e çekildi.
- Düzeltme: HOSTS dosyası okunamıyorsa hata yönetimi – tekrar güncellendi.

## [7.0] - 2021-04-08
- Yeni: Temizleme işleminden önce ne kadar alan boşalacağını gösterme.
- Düzeltme: HOSTS dosyası okunamıyorsa hata yönetimi.

## [6.9] - 2021-04-03
- Yeni: Common Apps içine MEGAsync eklendi.
- Taşındı: Sessiz Uygulama Yükleme’yi Devre Dışı Bırak, Otomatik Güncellemeleri Devre Dışı Bırak altına alındı.
- İyileştirme: Gizlilik Ayarlarını Devre Dışı Bırak artık daha akıcı.

## [6.8] - 2021-03-12
- Yeni: Common Apps içerisine Visual C++ AiO, .NET Frameworkler ve ViPER4Windows eklendi.
- Yeni: Hata kaydı (error logging).
- İyileştirme: Common Apps sürümleri güncellendi.
- İyileştirme: UI parlatma.

## [6.7] - 2021-02-25
- Düzeltme: Arama çalışmıyordu (Superfetch’i sıfırlayın, tekrar devre dışı bırakın ve Windows’u yeniden başlatın).

## [6.6] - 2021-02-24
- Düzeltme: Superfetch hizmetini devre dışı bırakırken çökme.

## [6.5] - 2021-02-23
- Düzeltme: Sessiz çalışırken bazı seçeneklerin kaydedilmemesi.
- Yeni: Bildirim Merkezi’ni devre dışı bırakma seçeneği (Windows 10).
- Yeni: Dosya uzantılarını ve gizli dosyaları gösterme (Performans İyileştirmelerini Etkinleştir).
- İyileştirme: Telemetry görev ve hizmetlerini devre dışı bırakma.
- İyileştirme: Superfetch devre dışı bırakma.
- İyileştirme: Game Bar devre dışı bırakma (daha fazla hizmet dahil).
- İyileştirme: Otomatik Güncellemeleri Devre Dışı Bırak.
- Küçük UI parlatmaları.

## [6.4] - 2021-02-22
- Düzeltme: Windows 7’de çökme sorunu giderildi.
- Düzeltme: SystemResponsiveness 0’dan 1’e değiştirildi (0, aslında 10 olarak sayılıyor).

## [6.3] - 2021-02-15
- Yeni: Common Apps, linkleri çevrimiçi alıyor; yeni linkler için uygulamayı güncellemeniz gerekmiyor.
- İyileştirme: UI ve arka planda tonla hata düzeltmesi.

## [6.2] - 2021-02-14
- Yeni: Onay kutuları ve radio butonlar için hoş bir stil.

## [6.1] - 2021-02-14
- İyileştirme: Windows Defender’ı devre dışı bırakma.
- İyileştirme: OneDrive kaldırma ve tüm kalıntıları temizleme.
- İyileştirme: Kaldırılamayan UWP uygulamaları gizleme seçeneği.
- Chromium linkleri güncellendi.
- Küçük UI düzeltmeleri.

## [6.0] - 2021-01-20
- Daha küçük pencere boyutu, Ortak Uygulamalar’da kaydırılabilir liste.

## [5.9] - 2021-01-19
- Düzeltme: Common Apps içinde klasör açarken çökme.

## [5.8] - 2020-12-22
- Eklendi: Common Apps içine Rufus ve Universal USB Installer.

## [5.7] - 2020-12-20
- Eklendi: Common Apps içine F.lux.

## [5.6] - 2020-12-20
- Düzeltme: Telemetry Hizmetlerini Devre Dışı Bırak.

## [5.5] - 2020-12-19
- Eklendi: Common Apps içinde daha fazla uygulama desteği.
- İyileştirme: Windows Defender’ı devre dışı bırakma.

## [5.4] - 2020-12-17
- Eklendi: İndirdikten sonra uygulamaları çalıştırma ve kurma seçeneği.
- Uygulama indirme bileşeniyle ilgili kritik hata düzeltmeleri.
- MSI paketlerini düzgün kaydetme.

## [5.3] - 2020-12-17
- Eklendi: Common Apps içinde ikonlar.
- Eklendi: Ek uygulamalar için indirme desteği.
- Çeşitli hata düzeltmeleri.
- UI parlatma.

## [5.2] - 2020-12-17
- Eklendi: Common Apps – Faydalı uygulamaları hızlıca toplu indirme.
- İyileştirme: Telemetry Hizmetlerini Devre Dışı Bırak.

## [5.1] - 2020-12-11
- Bazı UI uyarıları.

## [5.0] - 2020-12-10
- Eklendi: “Cihaza Yayınla (Cast to Device)” seçeneğini kaldırma.
- Eklendi: HOSTS editöründe hazır reklam engelleme listesi.
- Eklendi: "/unsafe" parametresi ile Windows Server’da Optimizer çalıştırma.
- İyileştirme: Daha hızlı HOSTS dosyası okuma.
- İyileştirme: Ağ kısıtlamasını devre dışı bırakma (Disable Network Throttling).
- Kaldırıldı: Skype reklamlarını engelleme (artık gereksiz).

## [4.9] - 2019-11-07
- Eklendi: Yapılandırma dosyası kullanarak Optimizer’ı sessiz modda çalıştırma.
- Eklendi: Windows Store otomatik güncellemelerini devre dışı bırakma (Disable Silent App Install).

## [4.8] - 2019-05-12
- Eklendi: Yapışkan Tuşlar’ı devre dışı bırakma (mevcut kullanıcı için).
- Eklendi: Uzun yolları etkinleştirme (Windows 10’da 260 karakter sınırını kaldırır).

## [4.7] - 2019-02-03
- Eklendi: Windows 10 1809 için Bulut Panosu (Cloud Clipboard) deneyimini devre dışı bırakma.

## [4.6] - 2019-01-30
- HOSTS editöründe engellenen IP, 127.0.0.1’ten 0.0.0.0’a değiştirildi.
- ‘Yeniden Başlat’ butonunun adı ‘Uygula ve Yeniden Başlat’a (Apply & Restart) değiştirildi.

## [4.5] - 2018-10-08
- İyileştirme: Seçenekler → Güncelleme kontrolü ile uygulamayı otomatik güncelleyebilirsiniz.

## [4.4] - 2018-09-21
- İyileştirme: Windows 10’da Otomatik Güncellemeleri devre dışı bırakma.
- Eklendi: HOSTS dosyasını salt okunur yapma.

## [4.3] - 2018-09-17
- Eklendi: SmartScreen’i devre dışı bırakma.

## [4.2] - 2018-09-12
- İyileştirme: Sessiz Uygulama Yükleme’yi devre dışı bırakma (Cloud Content).
- İyileştirme: Cortana ve web aramasını devre dışı bırakma.

## [4.1] - 2018-03-09
- Eklendi: Windows 10’da zorunlu özellik güncellemelerini devre dışı bırakma.

## [4.0] - 2018-02-21
- Eklendi: Faks hizmetini devre dışı bırakma.
- Eklendi: Windows Insider hizmetini devre dışı bırakma.

## [3.9] - 2018-01-05
- Eklendi: Program Uyumluluk Yardımcısı Hizmeti’ni devre dışı bırakma.
- Eklendi: Seçenekler içinde yeni sürüm kontrolü.
- Eklendi: Değişiklikleri görüntüleme (View changes) seçeneği.

## [3.8] - 2017-12-31
- Windows 7 çökme sorunu düzeltildi.

## [3.7] - 2017-12-22
- Artık her seçenek geri alınabiliyor (anahtarlar, nihayet).
- Uygula Tüm (Apply All) butonu kaldırıldı; yerine anahtarlar (toggles) kullanılıyor.
- Windows 10 için Karanlık Tema’yı etkinleştirme anahtarı eklendi.
- Telemetri Hizmetlerini devre dışı bırakma, birden fazla servisi tek anahtarda topladı.
- "Windows 10 Edin" butonunu kaldırma seçeneği gereksiz olduğu için kaldırıldı.
- Çeşitli iyileştirmeler.
- Seçenekler içinde Yapılandırmayı Sıfırla butonu eklendi.

## [3.6] - 2017-12-11
- UWP kaldırıcı içinde Tümünü Seç (Select All) eklendi.
- Telemetry görevlerini devre dışı bırakma iyileştirildi.
- Otomatik Güncellemeleri devre dışı bırakmada değişiklikler.

## [3.5] - 2017-11-24
- UWP uygulama kaldırıcı geri eklendi.
- Windows Defender’ı devre dışı bırakmak artık tepsi simgesini de kaldırıyor.
- Başlat Menüsü reklamlarını devre dışı bırakma ve Sessiz Uygulama Yükleme iyileştirildi.
- Görev Çubuğu rengini geri yükleme seçeneği eklendi.
- Küçük görsel değişiklikler.
- “Sync Provider” reklamlarını gizleme, “Hızlı Erişim Geçmişini Devre Dışı Bırak” olarak yeniden adlandırıldı (kullanılan dosya ve klasörleri gizler, Dosya Gezgini ‘Bu Bilgisayar’ ile açılır).

## [3.4] - 2017-10-25
- Performans iyileştirmeleri.
- x86 sistemlerde başlangıçta çökme düzeltildi.

## [3.3] - 2017-10-21
- Gizlilik seçeneklerini devre dışı bırakma iyileştirildi.
- Windows Ink ve önerileri devre dışı bırakma seçeneği eklendi.
- Yazım denetimi ve yazma özelliklerini devre dışı bırakma seçenekleri eklendi.

## [3.2] - 2017-10-18
- Windows 10 Fall Creators Update ile uyumlu.
- Xbox Live’ı devre dışı bırakma ve Cortana’yı devre dışı bırakma seçenekleri geliştirildi.
- Görev çubuğundan “My People” ikonunu kaldırma seçeneği eklendi.
- Windows Update’ten sürücüleri hariç tutma seçeneği eklendi.

## [3.1] - 2017-09-26
- Windows 10’da Başlat Menüsü reklamlarını devre dışı bırakma.
- Windows 10’da Modern Uygulamaların yeniden yüklenmesini engelleme.

## [3.0] - 2017-06-28
- Medya Oynatıcı paylaşım hizmetini devre dışı bırakma seçeneği eklendi.
- Windows 10 için çeşitli gizlilik iyileştirmeleri.

## [2.9] - 2017-05-17
- Çalıştır (Run) penceresi için özel komutları kaldırma özelliği eklendi.

## [2.8] - 2017-05-16
- Telemetry görevlerini devre dışı bırakma daha da iyileştirildi.

## [2.7] - 2017-04-04
- Windows 10 Creators Update ile uyumlu.
- Sensor Services’i etkinleştirme/devre dışı bırakma seçeneği eklendi.
- Hosts editöründe alan adı engelleme seçeneği eklendi.

## [2.6] - 2017-03-14
- Küçük görsel düzeltmeler.

## [2.5] - 2017-02-18
- Çok sayıda hata sebebiyle Modern Uygulamaları kaldırma özelliği geçici olarak kaldırıldı.

## [2.4] - 2017-02-17
- Kayıt defteri düzeltici (registry fixer) iyileştirildi.

## [2.3] - 2017-02-15
- Telemetry görevlerini devre dışı bırakma geliştirildi.
- Yeni performans ince ayarları eklendi.

## [2.2] - 2016-12-14
- Küçük hata düzeltmeleri.

## [2.1] - 2016-12-05
- Integrator hazır menülerine “Sahipliği Al (Take Ownership)” seçeneği eklendi.
- Genel iyileştirmeler.

## [2.0] - 2016-11-24
- Küçük hata düzeltmeleri.
- Görsel (cosmetic) değişiklikler.

## [1.9] - 2016-11-14
- Office Telemetry’yi devre dışı bırakma daha da geliştirildi.

## [1.8] - 2016-10-27
- Daha fazla hata düzeltmesi.

## [1.7] - 2016-10-23
- Küçük hata düzeltmeleri.

## [1.6] - 2016-10-20
- Windows 10’da Game Bar’ı devre dışı bırakma seçeneği eklendi.

## [1.5] - 2016-09-14
- Büyük hata düzeltmeleri.

## [1.4] - 2016-09-12
- HOSTS editörü eklendi.
- Integrator aracı eklendi.
- Tema seçeneği eklendi.
- Performans iyileştirmeleri.
- Görsel değişiklikler.

## [1.3] - 2016-09-09
- Başlangıç öğeleri algılama iyileştirildi.

## [1.2] - 2016-09-08
- Windows 10 Yıldönümü Güncellemesi (Anniversary Update) ile uyumlu.
- Küçük görsel düzeltmeler.

## [1.1] - 2016-08-05
- Yazdırma Hizmeti’ni etkinleştirme/devre dışı bırakma seçeneği eklendi.
- Office Telemetry’yi devre dışı bırakma iyileştirildi.
- Büyük hata düzeltmeleri.

## [1.0] - 2016-07-26
- İlk sürüm (Initial release).
