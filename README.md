select * from employees; --employees tablosundaki sütunların adlarını görebilmek için hepsini çağırıp baktım

select FirstName, lastname, salary from employees; --bizden istenen sütunları belirtilen tablodan çağırdık

select distinct Departmentid from employees; --kaç çeşit departman olduğunu görebilmek için distinct ifadesini kullanıyoruz

select * from employees where departmentid = 1; --departmentid kısmında sadece rakam çıktığını görüyoruz. departments tablosundan IT'ye karşılık gelen sayıyı seçip
--where komututla IT olanları getirtiyoruz.

select * from employees order by salary desc; --maaşların ve çalışan bilgilerini desc kullanmadan yapsaydık küçükten büyüğe olacaktı o yüzden desc kullandık.

select firstname || ' ' || lastname as tam_ad from employees; --yayında Tuncay beyin gösterdiği gibi yapmaya çalıştım.

--Her satır ödevde istenilen maddelere denk geliyor.
