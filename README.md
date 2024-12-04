
# Student-Dtails-Record-System---SQL
SQL using to Stored Data
insert into Personal values ('1','R Sangeetha','2003-11-13','M.com','S.Ravi','8 south street virudhunagar'),('2','G.Saranya','2002-11-01','B.E(CSE)','A.Ganesan','12,main bazzar,Srivilliputur'),('3','A.Mufty mohamed','2003-10-03','M.Sc','M.Ali','67,Theni main road,Kambam'),('4','J.spergeon','2003-02-05','MCA','J,John','156,Nadarstreet,watrap');
select* from Personal;
insert into PD values('1','S.Ravi','coolie','82000','R.Sankari','no','0'),('2','A.Ganesan','Business','120000','G.Devi','no','0'),('3','M.Ali','lawer','150000','A.Mymoon','no','0'),('4','J.John','Docter','210000','J.Merry','no','0');
select * from PD;
insert into sports values('1','No','No','Yes','No'),('2','No','Yes','No','No'),('3','No','No','No','Yes'),('4','Yes','No','No','No')
select * from sports;
insert into Transports values('1','Yes',' south street virudhunagar','Kalasalingam University','Yes','14000','No','0'),
('2','Yes','main bazzar,Srivilliputur','Kalasalingam University','No','0','Yes','18000'),
('3','No','-','-','No','0','No','0'),
('4','No','-','-','No','0','No','0');
select * from Transports;
insert into CD values('1','7604961578','sangetha11@gmail.com','7864329017','ravi4321@gmail.com'),
('2','8870646276','saran6321@gmail.com','9934650125','ganesan1122@gmail.com'),
('3','9894112825','mohamed0410@gmail.com','9062718362','ali786@gmail.com'),
('4','9025044131','peter34567@gmail.com','8743761037','john9876@gmail.com');
select * from CD;
insert into skill values('1','-','Yes','-','-','-'),('2','Yes','-','-','-','-'),('3','-','-','-','Yes','-'),('4','-','-','Yes','-','-');
insert into Mess values('1','No','-','-','-','-'),('2','No','-','-','-','-'),('3','Yes','Yes','80000','-','-'),('4','No','-','-','-','-');
select * from Mess;
select * from Personal;
select * from PD
select * from CD
select * from Transports
select * from skill
select * from sports
select * from Hostel
select * from skill;
insert into Hostel values('1','No','-','-','-','-','-','-'),('1','No','-','-','-','-','-','-'),('1','Yes','-','-','Yes','120000','-','-'),('4','No','-','-','-','-','-','-');
select * from Hostel;


delete from Mess where [s no]='1'

\\\\\insert into id values(1,(select * from openrowset(bulk 'D:sql\sql projects\20', single_blob) as image));\\\\\\\\
\\\\\\insert into id values('1',load values ('D:\\sql\\sql projects\\20.jpg'));\\\\\\

# Student-Details-Record-System
SQL using to Stored Data
