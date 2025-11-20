# Cloudflare Worker Proxy

[中文](README_CN.md)

## Contoh Penggunaan

Contoh:

[https://proxy.liyao.space/------https://www.tsukuba.ac.jp/](https://proxy.liyao.space/------https://www.tsukuba.ac.jp/)
[https://proxy.liyao.space/------https://www.jlu.edu.cn/](https://proxy.liyao.space/------https://www.jlu.edu.cn/)
[https://proxy.liyao.space/------https://news.ycombinator.com](https://proxy.liyao.space/------https://news.ycombinator.com)

Kamu juga bisa langsung membuka situsnya lalu memasukkan URL secara manual:

[https://proxy.liyao.space/](https://proxy.liyao.space/)
[https://webproxy.stratosphericus.workers.dev/](https://webproxy.stratosphericus.workers.dev/)

Tautan-tautan contoh ini menunjukkan cara proxy bekerja ketika mengakses situs web sederhana.

## Petunjuk Penggunaan

1. Deploy sebuah Worker di Cloudflare.
2. **Ubah nilai `proxyDomains`** dalam kode agar sesuai dengan konfigurasi domain Worker-mu.
3. Klik “Deploy”, lalu gunakan sesuai contoh di bagian atas.

## Hal yang Perlu Diperhatikan

* Pastikan konfigurasi routing Cloudflare Worker sudah benar.
* Pastikan `proxyDomains` sudah diubah agar sesuai dengan nama domain yang kamu gunakan.

## Distribusi Permintaan

*(gambar seperti di README asli)*

## Riwayat Star

[![Star History Chart](https://api.star-history.com/svg?repos=BH3GEI/CloudflareWorkerProxy\&type=Date)](https://www.star-history.com/#BH3GEI/CloudflareWorkerProxy&Date)

