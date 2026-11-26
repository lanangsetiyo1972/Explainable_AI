HASIL AUDIT ROBUSTNESS TAHAP A — DSS Desa Wisata
02_screening_12_kombinasi.csv : ablasi x 3 model (eksploratif, train only)
03_nested_folds.csv : pemilihan model dan threshold INNER per outer fold
03_nested_oof_predictions.csv : prediksi outer OOF; tidak menyentuh holdout lama
04_nested_metrics_per_repeat.csv : evaluasi per repeat, bukan pengamatan independen
05_bootstrap_95CI.csv : CI berpasangan tingkat desa atas repeat pertama
06_group_holdout_kabupaten.csv : sensitivitas berdasarkan kabupaten/kota
07_precision_recall_nested.png : kurva OOF train-only
07_frekuensi_pemilihan_kandidat.csv : kestabilan kandidat terpilih
08_model_A_train_only.joblib : calon model A (latih saja 1068 desa)
08_model_A_metadata.json : threshold, fitur, konfigurasi
Label di luar benchmark tidak sama dengan kelas resmi negatif JADESTA.
DILARANG menggunakan ulang holdout yang sebelumnya sudah dilihat untuk mengklaim hasil baru independen.
Hasil model A belum otomatis kompatibel dengan SHAP lama hingga model A+B DSS ditetapkan ulang.
