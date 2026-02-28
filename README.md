# 🛡️ K-CMD // Siber Komuta Merkezi

**K-CMD**, etik hackerlar ve sızma testi uzmanları için geliştirilmiş, minimalist ve yüksek performanslı bir operasyon yönetim panelidir. Tüm araçlarınızı tek bir merkezden yönetin.

---

## 🚀 Öne Çıkan Özellikler

* 🎯 **Quick Tools:** Nmap, Sqlmap ve Metasploit komutlarını tek tıkla kopyalayın.
* 🌐 **Target Management:** Hedef sistemlerin durumunu ve zafiyetlerini takip edin.
* 📚 **Bilgi Bankası:** Kritik portlar ve siber güvenlik terimleri her an elinizin altında.
* 💾 **Local Sync:** Notlarınızı tarayıcı hafızasında güvenle saklayın.

---

## 📡 Port Analiz & Strateji Rehberi

| Port | Servis | Önem Derecesi | Tipik Saldırı Vektörü |
| :--- | :--- | :--- | :--- |
| **21** | FTP | 🟡 Orta | Anonymous Login / Brute-force |
| **22** | SSH | 🔴 Yüksek | Exploit (LibSSH) / Key Auth |
| **80/443** | HTTP/S | 🔴 Yüksek | Web Vulnerabilities (SQLi, XSS) |
| **445** | SMB | 💀 Kritik | Remote Code Execution (EternalBlue) |
| **3389** | RDP | 💀 Kritik | BlueKeep / Credential Stuffing |

---

## 📖 Siber Güvenlik Sözlüğü

* **Exploit:** Bir sistemdeki açıktan yararlanmak için kullanılan yöntem veya kod.
* **Payload:** Sızma sonrası hedef sistemde çalıştırılacak olan asıl işlevsel kod.
* **Reverse Shell:** Hedef makinenin, saldırgana geri bağlantı kurmasını sağlayan yöntem.
* **Privilege Escalation:** Düşük yetkili bir kullanıcıdan yetkili (Root/Admin) seviyesine çıkma.

---

## 🛠️ Kurulum ve Çalıştırma

Bu projeyi bilgisayarınıza klonlamak için terminale şu komutu yazın:

```bash
git clone [https://github.com/apo536098-wq/K-CMD.git](https://github.com/apo536098-wq/K-CMD.git)

Çalıştırma:

1.  Klasöre gidin: cd K-CMD

2.  index.html dosyasını favori tarayıcınızla (Chrome, Firefox, Edge vb.) açın.

⚠️ Yasal Uyarı (Disclaimer)
Bu araç sadece eğitim ve etik sızma testleri amacıyla geliştirilmiştir. İzinsiz sistemlere karşı kullanımı yasal sorumluluk doğurabilir. Kullanıcı, yaptığı eylemlerden bizzat sorumludur.

Geliştirici: [Kadir]

💡 Katkıda Bulunun
Bu proje açık kaynaklıdır. Yeni araçlar eklemek veya tasarımı geliştirmek için bir Pull Request açabilirsiniz!
