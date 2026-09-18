# sistem-panen
sistem panen TTS minggu 4
print("Sistem Pencatatan Hasil Panen")

def laporan(data):
    print("===== LAPORAN HASIL PANEN =====")

    for komoditas, jumlah in data:
        print(f"Komoditas: {komoditas}")
        print(f"Jumlah: {jumlah} kg")
