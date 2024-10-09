## CARA MENGATASI NV DATA CORRUPTED REDMI 10A
#### PENJELASAN SINGKAT
> [!IMPORTANT]
  _NV data is corrupted ini sering terjadi di hp mediatek yang sudah di oprek, dikarenakan **_Scurrity image_** error atau **_IMEI hilang_**. Dan biasanya terjadi karena menggunakan custom rom dan setelah melakukan flash firmware di tools seperti SP flash tool, **_lah apa salahnya??_** mungkin flash data systemnya error dan lupa format data saat mengganti rom. Lalu bagaimana cara memperbaiki masalah NV data is corrupted?_

## SEBELUM EKSEKUSI PERSIAPKAN:
- **nyali**
- **laptop/pc yang sehat**
- **kabel usb**
- **file firmware redmi 10A [download disini](https://xmfirmwareupdater.com/miui/dandelion/stable%20beta/V12.5.5.0.RCZIDXM/)**
- **file NV redmi 10A [download disini](https://github.com/axxescript/nv-data-is-corrupted-redmi-10a-fix/releases/tag/by_axxescript)**
- **driver mtk dan libusb filter**
- **SP flash tool [download disini](https://spflashtools.com/) atau TFT MTK MODULE [download disini](https://bestflashfile.com/tft-mtk-module-tool/)**
 
## CARA PERTAMA 
###### Memasang ulang super.img di mode fastboot
1. Download _minimal-adb-fastboot_ di laptop/pc kalian
2. Extrack file _minimal-adb-fastboot_ di disk C:/
3. Copy/cut file super.img di file firmware lalu paste di folder minimal_adb_fastboot
4. Klik 2x pada file cmd_here.exe
5. Lalu mulai ulang hp Redmi 10A kalian ke mode fastboot tekan VOL [-] + POWER tahan sampai masuk ke mode fastboot
6. Sambungkan hp kalian ke laptop/pc
7. Masukan kode ini di _cmd_here.exe_:
   ```
   fastboot device
   fastboot flash super super.img
   fastboot reboot

   ```
<sub>LIHAT HASILNYA


##  CARA KEDUA
> [!WARNING]
> _cara kedua ini sedikit beresiko dan membutuhkan nyali silahkan meminta bimbingan dari seseorang yang lebih profesional_
###### Memulihkan data NV menggunakan tool SP Flash Tool
1. Extrack file NV redmi 10a
2. Pasang driver MTK dan LibUsb Filter
3. Buka SP Flash Tool dan MTK BYPASS rev3/4
4. Power off hp redmi 10a
5. Tekan dan tahan VOL [-] & VOL [+] beberapa detik lalu colok usb, nanti akan muncul _MTK USB PORT_ di LibUsb lalu dengan cepat kalian install MTK usb port di LibUsb.
6. Lanjut Bypass Mode Brom di MTK BYPASS, caranya sama Tahan VOL [-] & VOL [+] beberapa detik lalu colok usb
7. Buka SP Flash Tool lalu pilih file MTK6765_Android_scatter.txt di Folder file_nv_redmi10a/images lalu enter
8. Setelah itu langsung exsekusi klik "DOWNLOAD"

<sub>SELESAI

### SUBSCRIBE
- **[AxxeScript](https://youtube.com/@AxxeScript)**


## CONTACT SAYA
- [youtube](https://youtube.com/@AxxeScript)
- [Telegram](https://t.me/@AxxeBD)
- [Email](mailto:axxescript@gmail.com)




### PENUTUP

> _Trimakasih sudah membaca jangan lupa starnya hehe :+1:. Jika ada kesalahan pada penjelasan dan tutorial dari saya mohon berikan komentar di [Issue](https://github.com/axxescript/nv-data-is-corrupted-redmi-10a-fix/issues/1)._


## License

    SFPS, including all git submodules are free software:
    you can redistribute it and/or modify it under the terms of the
    GNU General Public License as published by the Free Software Foundation,
    either version 3 of the License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
