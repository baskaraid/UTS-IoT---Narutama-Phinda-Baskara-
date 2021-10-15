<h1> Alur Dari Script Ini </h1>
Alur dari script ini terdapat 2 rumah yang memiliki fire monitor dengan kondisi masing masing
jika ada api di dalam rumah tersebut atau kebakaran Garage, Window, Keran atau Fire Sprinkler, Pintu akan terbuka semua
agar Pemilik rumah tersebut bisa lari dari rumah tersebut yang terbakar dan lampu, Ac dan kipas Mati mengantisipasi konsleting di akibatkan adanya Air dari Keran Fire Sprinkler yang menyemprotkan air

<h1> Kode Program </h1>
setDeviceProperty(getName(), 'IR', 900);
sensor api ke LED yang telah dimodifikasi untuk memeriksa sinyal digital, ketika api jauh dari IR maka akan mati dan jika terlalu dekat akan nyala
