DSS DESA WISATA — CATATAN PENELITIAN
Dataset 0/1/2 = di luar benchmark / Maju / Mandiri. BELUM diverifikasi JADESTA.
Model hierarkis A: luar vs maju+mandiri; B: maju vs mandiri.
Model dan threshold ditentukan pada training; holdout dipakai sekali untuk laporan.
Hasil semua desa = in-sample deployment, BUKAN validasi independen.
Skor Mandiri adalah keluaran model, bukan status resmi, probabilitas transisi, atau dampak kausal.
SHAP dijalankan langsung ke fungsi skor akhir A*B tanpa XGBoost.
Lihat manifest JSON untuk konfigurasi.
