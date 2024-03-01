saya melakukan beberapa pengujian:

1. 
Number thread (users) = 3
Ramp-up period (second) = 15
Loop = 1

2024-03-01 12:44:39,718 INFO o.a.j.t.JMeterThread: Thread started: workLoadConfig 1-1
2024-03-01 12:44:44,720 INFO o.a.j.t.JMeterThread: Thread started: workLoadConfig 1-2
2024-03-01 12:44:49,721 INFO o.a.j.t.JMeterThread: Thread started: workLoadConfig 1-3

2024-03-01 12:44:42,224 INFO o.a.j.t.JMeterThread: Thread finished: workLoadConfig 1-1
2024-03-01 12:44:47,172 INFO o.a.j.t.JMeterThread: Thread finished: workLoadConfig 1-2
2024-03-01 12:44:51,958 INFO o.a.j.t.JMeterThread: Thread finished: workLoadConfig 1-3

selisih  = 2-3 detik
Note: saya mengambil dari waktu eksekusi start dan finish


2.
Number thread (users) = 2
Ramp-up period (second) = 10
Loop = 1

rentang waktu ekseskusi yang didapat adalah 4 detik
dilihat dari (1-1) ke (1-2), (1-2) ke (1-3)

2024-03-01 12:43:06,710 INFO o.a.j.t.JMeterThread: Thread started: workLoadConfig 1-1
2024-03-01 12:43:11,709 INFO o.a.j.t.JMeterThread: Thread started: workLoadConfig 1-2

2024-03-01 12:43:09,389 INFO o.a.j.t.JMeterThread: Thread finished: workLoadConfig 1-1
2024-03-01 12:43:14,201 INFO o.a.j.t.JMeterThread: Thread finished: workLoadConfig 1-2

selisih  = 3-5 detik
Note: saya mengambil dari waktu eksekusi start dan finish


3. 
Number thread (users) = 10
Ramp-up period (second) = 2
Loop = 1


2024-03-01 12:38:42,872 INFO o.a.j.t.JMeterThread: Thread started: workLoadConfig 1-1
2024-03-01 12:38:43,373 INFO o.a.j.t.JMeterThread: Thread started: workLoadConfig 1-2
2024-03-01 12:38:43,869 INFO o.a.j.t.JMeterThread: Thread started: workLoadConfig 1-3

2024-03-01 12:38:44,675 INFO o.a.j.t.JMeterThread: Thread finished: workLoadConfig 1-1
2024-03-01 12:38:45,010 INFO o.a.j.t.JMeterThread: Thread finished: workLoadConfig 1-2
2024-03-01 12:38:45,441 INFO o.a.j.t.JMeterThread: Thread finished: workLoadConfig 1-3

selisih  = 2 detik
Note: saya mengambil dari waktu eksekusi start dan finish, saya mengambil 3 sampel.