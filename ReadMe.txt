1-Bilgisayarınız hizmetler bölümünden SQL Server durdurun.
2-SQL Database klasöründe bulunan dosyaları bilgisayarınızın SQL Server database'ine kopylayın.(C:\Program Files\Microsoft SQL Server\MSSQL14.SQLEXPRESS\MSSQL\DATA)
3-SQL Server Management Studio yönetici olarak açın.
4-Databases sağ tık Attach basın.Add bölümünden kopyaladığınız database seçin daha sonra OK basın.
5-Visual Studio projesini açın.
6-Scada.DAL sınıfı , Connection klasörü içinde DBConnection.cs içinde SQL Server yolunu kendi bilgisayarınıza göre ayarlayın.

1-Stop SQL Server from your computer services section.
2-Copy the files in the SQL Database folder to your computer's SQL Server database.
3-Open SQL Server Management Studio as an administrator.
4-Right click on databases, press Attach. Select the database you copied from add, then press OK.
5-Open the Visual Studio project.
6-In the Scada.DAL class, in the Connection folder, set the SQL Server path in DBConnection.cs to your own computer.