# Contoh algoritma deteksi stres menggunakan data GSR dan HRV
def stress_detection(gsr_value, hrv_value):
    if gsr_value > 6 μS and hrv_value < 50 ms:
        return "High Stress"
    elif 4 μS < gsr_value ≤ 6 μS and 50 ms ≤ hrv_value < 70 ms:
        return "Moderate Stress"
    else:
        return "Normal"
