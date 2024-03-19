![](docs/images/logo.png)

[![Downloads](https://img.shields.io/badge/dynamic/json?color=green&label=Downloads&query=totalString&url=https%3A%2F%2Fraw.githubusercontent.com%2Ftopjohnwu%2Fmagisk-files%2Fcount%2Fcount.json&cacheSeconds=1800)](https://raw.githubusercontent.com/topjohnwu/magisk-files/count/count.json)

#### Ini adalah repository clone dari versi aslinya. Aplikasi pihak ketiga tidak di dukung oleh Google maupun android. Aplikasi ini open source oleh komunitas pengembang.

## Mengenal Magisk

Magisk adalah aplikasi dengan kode sumber terbuka untuk mengkusotomisasi android, dan memberikan hak akses lebih.  Mendungkung android versi 6.0, hingga atasnya.<br>
Beberapa fitur Magisk:

- **MagiskSU**: Menyediakan hak izin akses root pada aplikasi lain.
- **Magisk Modules**: Plugin untuk memodidikasi partisi menjadi Hanya Baca.
- **MagiskBoot**: Alat untuk melakukan backup ( packing ) dan restore ( unpacking ) file image ( os ) android.
- **Zygisk**: Plugin untuk menjalankan kode di setiap proses aplikasi.

## Downloads

[Github](https://github.com/topjohnwu/Magisk/) Silakan unduh magisk lewat repositori aslinya, mengunduh dari repositori ini dapat menyebabkan masalah keamanan. Versi ini hanya untuk saya sendiri, tidak untuk publik, tapi anda bisa menyalin repositori ini untuk dimodifikasi sendiri. Tautan di bawah ini mengarah ke repositori asli.

[![](https://img.shields.io/badge/Magisk-v27.0-blue)](https://github.com/topjohnwu/Magisk/releases/tag/v27.0)
[![](https://img.shields.io/badge/Magisk%20Beta-v27.0-blue)](https://github.com/topjohnwu/Magisk/releases/tag/v27.0)
[![](https://img.shields.io/badge/Magisk-Canary-red)](https://raw.githubusercontent.com/topjohnwu/magisk-files/canary/app-release.apk)
[![](https://img.shields.io/badge/Magisk-Debug-red)](https://raw.githubusercontent.com/topjohnwu/magisk-files/canary/app-debug.apk)

## Useful Links

- [Installation Instruction](https://topjohnwu.github.io/Magisk/install.html)
- [Building and Development](https://topjohnwu.github.io/Magisk/build.html)
- [Magisk Documentation](https://topjohnwu.github.io/Magisk/)

## Bug Reports

**Only bug reports from Debug builds will be accepted.**

For installation issues, upload both boot image and install logs.<br>
For Magisk issues, upload boot logcat or dmesg.<br>
For Magisk app crashes, record and upload the logcat when the crash occurs.

## Translation Contributions

Default string resources for the Magisk app and its stub APK are located here:

- `app/src/main/res/values/strings.xml`
- `stub/src/main/res/values/strings.xml`

Translate each and place them in the respective locations (`[module]/src/main/res/values-[lang]/strings.xml`).

## License

    Magisk, including all git submodules are free software:
    you can redistribute it and/or modify it under the terms of the
    GNU General Public License as published by the Free Software Foundation,
    either version 3 of the License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
