# VeriVeren

**VeriVeren** sürüm deposuna hoş geldiniz!

Bu depo, Windows ve macOS için derlenmiş en son uygulama dosyalarını içerir. `.exe`, `.dmg` veya `.zip` dosyalarını [Releases](https://github.com/ahmetkurnaz/VeriVeren/releases) sekmesinden indirebilirsiniz.

---

## 🪟 Windows Kurulumu

1. [Releases](https://github.com/ahmetkurnaz/VeriVeren/releases/tag/v0.0.4) sekmesinden en son `.exe` veya `.zip` dosyasını indirin.
2. Kurulum yapacaksanız:
   - `.exe` dosyasına çift tıklayın ve ekrandaki talimatları izleyin.
3. Sıkıştırılmış `.zip` kullandıysanız:
   - Dosyayı çıkarın ve `VeriVeren.exe` dosyasını çalıştırın.

> ⚠️ Windows, imzasız uygulamalar için uyarı verebilir. **“More info (Daha fazla bilgi)” → “Run anyway (Yine de çalıştır)”** seçerek devam edebilirsiniz.

---

## 🍏 macOS Kurulumu

1. [Releases](https://github.com/ahmetkurnaz/VeriVeren/releases/tag/v0.0.5) bölümünden `.dmg` dosyasını indirin.
2. `.dmg` dosyasını açın ve **VeriVeren uygulamasını `Applications` klasörüne sürükleyin**.
3. Uygulamayı ilk kez açtığınızda şu uyarıyı görebilirsiniz:

   > “VeriVeren” açılamıyor çünkü Apple bu uygulamayı zararlı yazılımlara karşı denetleyemiyor.

### ✅ Bu uyarıyı aşmak için:

#### macOS Ventura / Sonoma (ve sonrası):

1. **Sistem Ayarları → Gizlilik ve Güvenlik** menüsüne gidin.
2. Aşağıya kaydırın. “VeriVeren uygulamasının açılmasına izin verilmiyor” mesajını bulun.
3. Yanındaki **“Yine de Aç”** butonuna tıklayın ve açmayı onaylayın.

#### VEYA Terminal ile aç (ileri düzey kullanıcılar için):

Eğer yukarıdaki buton çıkmazsa, Terminal’i açıp şu komutları yazın:

```bash
sudo xattr -d com.apple.quarantine /Applications/VeriVeren.app
open /Applications/VeriVeren.app
```

=========================================================================================================
# ENGLISH
=========================================================================================================

# VeriVeren

Welcome to the **VeriVeren** release repository!

This repository contains the latest pre-built binaries for Windows and macOS. You can download the `.exe`, `.dmg`, or `.zip` files directly from the [Releases](https://github.com/ahmetkurnaz/VeriVeren/releases) section.

---

## 🪟 Windows Installation

1. Download the latest `.exe` or `.zip` file from the [Releases](https://github.com/ahmetkurnaz/VeriVeren/releases) section.
2. If using the installer:
   - Double-click the `.exe` file and follow the on-screen instructions.
3. If using the `.zip`:
   - Extract it anywhere and run `VeriVeren.exe`.

> ⚠️ Windows SmartScreen may show a warning (because the app is not code-signed). Click **"More info" → "Run anyway"**.

---

## 🍏 macOS Installation

1. Download the `.dmg` file from the [Releases](https://github.com/ahmetkurnaz/VeriVeren/releases).
2. Open the `.dmg` and **drag the VeriVeren app into your `Applications` folder**.
3. On first launch, macOS **may block the app** with a message like:

   > “VeriVeren” cannot be opened because Apple cannot check it for malicious software.

### ✅ To open the app anyway:

#### macOS Ventura / Sonoma (or newer):
1. Go to **System Settings → Privacy & Security**.
2. Scroll down and find a message about “VeriVeren” being blocked.
3. Click **“Open Anyway”**, then confirm.

#### OR use Terminal (advanced users):
If the button above doesn't appear:

```bash
sudo xattr -d com.apple.quarantine /Applications/VeriVeren.app
open /Applications/VeriVeren.app
```

