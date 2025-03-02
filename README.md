                        họ và tên: trần tấn phát      mã sinh viên
import numpy as np

import matplotlib.pyplot as plt


x = np.linspace(0, 10, 100)
y1 = np.sin(x)
y2 = np.cos(x)
y3 = np.sin(x) * np.cos(x)


plt.figure(figsize=(10, 6))  # Kích thước biểu đồ

plt.plot(x, y1, label="sin(x)", color="r", linestyle="--", linewidth=2, marker="o", markersize=4)
plt.plot(x, y2, label="cos(x)", color="b", linestyle="-.", linewidth=2, marker="s", markersize=4)
plt.plot(x, y3, label="sin(x) * cos(x)", color="g", linestyle="-", linewidth=2, marker="d", markersize=4)


plt.title("Biểu đồ Hàm Số", fontsize=14, fontweight="bold")
plt.xlabel("Giá trị X", fontsize=12)
plt.ylabel("Giá trị Y", fontsize=12)


plt.grid(True, linestyle="--", alpha=0.6)
plt.legend(loc="upper right", fontsize=12)


plt.show(play)

<!---
chiniue/chiniue is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
