# Application Architecture
**source**: [What is an application architecture? (redhat.com)](https://www.redhat.com/en/topics/cloud-native-apps/what-is-an-application-architecture)
Application architecture adalah deskripsi pola dan teknik yang digunakan dalam desain dan pembuatan aplikasi. Menjadi acuan dan standar developer saat melakukan pengembangan aplikasi. 
1. **Layered or N-tier Architecture**: Membagi aplikasi menjadi beberapa layer yang memiliki *responsibility* masing-masing. Setiap layer hanya bisa memanggil layer di bawahnya.
2. **Monolitic Architecture**: Sebuah unit aplikasi yang memiliki semua fungsionalitas. (*tightly coupled*)
3. **Microservices**: Aplikasi yang terdiri dari beberapa komponen independen yang memiliki fungsionalitas masing-masing.
4. **Event-driven Architecture**: Terdiri dari event producer dan event consumer. Event atau perubahan state, akan merepresentasikan event tersebut dengan sebuah *message*, dikirim ke event consumer lalu diproses secara asinkronus.
5. **Service-oriented Architecture (SOA)**: Membagi-bagi aplikasi menjadi beberapa services.
