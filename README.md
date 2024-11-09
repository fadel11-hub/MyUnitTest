1. Penamaan Kelas dan File
Gunakan UpperCamelCase untuk nama kelas. Contoh: UserProfile, UserRepository, RecyclerViewAdapter.
Jika kelas meng-extend komponen Android, tambahkan nama komponen tersebut di akhir kelas. Contoh: MainActivity, UserFragment, NotificationService.
2. Penamaan File Resources
Gunakan lowercase_underscore untuk file dalam folder res/.

Ikuti konvensi berikut untuk penamaan file drawable:

Tipe Aset	Awalan	Contoh
Action bar	ab_	ab_stacked.9.png
Button	btn_	btn_send_pressed.9.png
Icon	ic_	ic_star.png
Notification	notification_	notification_bg.9.png
Tabs	tab_	tab_pressed.9.png
File Layout: Nama file layout diawali dengan nama komponen yang memiliki layout tersebut, misalnya activity_main.xml, fragment_user.xml.

File Menu: Gunakan nama kelas yang terkait tanpa awalan menu_, misalnya activity_user.xml.

File Values: Gunakan nama jamak dalam bahasa Inggris, seperti strings.xml, styles.xml, colors.xml.
