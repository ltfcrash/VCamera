# VCamera
**This is an open source for android virtual camera.**  
*Just for protect your camera privacy.*


# demo video
[![Watch the video](https://img.youtube.com/vi/lT-MP9c7SbY/maxresdefault.jpg)](https://www.youtube.com/embed/lT-MP9c7SbY)


# Key Features
**1. Support replacing the camera with a photo.**
**2. Support replacing the camera with video.**
**3. Support to replace the camera with network video.**
**4. Support to replace the camera with network video.**
**4. Support resizing video, rotating, moving, zooming, flipping, etc.**


# Strategi Kompatibilitas dan Stabilitas (Android 15+)
- **Prioritaskan jalur non-root** dengan mengeksplorasi implementasi Virtual Camera melalui API resmi seperti MediaProjection atau Virtual Device/Display agar tetap stabil, aman, dan kompatibel dengan Google Play.
- **Pertimbangkan migrasi ke CameraX Extension** untuk skenario injeksi efek pada aplikasi yang memakai CameraX, sehingga mengurangi kebutuhan hooking sistem.
- **Optimalkan kode native** dengan memverifikasi dan mengompilasi ulang semua library NDK/C++ untuk mendukung ukuran halaman 16KB, guna menghindari risiko kompatibilitas terbesar di Android 15.
- **Kelola performa video menggunakan GPU** (Vulkan atau OpenGL ES) untuk pemrosesan frame, resizing, dan cropping agar beban CPU dan konsumsi daya lebih rendah.
- **Gunakan mediaProcessing FGS** saat streaming di latar belakang sehingga alokasi sumber daya tetap optimal dan sesuai regulasi Android 15.


# Contact Me
andvipgroup@gmail.com

# APK Download
**Latest version : 3.0.0**

[Github](https://github.com/andvipgroup/VCamera/releases)

[Google Play](https://play.google.com/store/apps/details?id=virtual.camera.app)

