#Comando iostat 

iostat -mxy 10

Linux 5.10.0-20-amd64 (hostname)    05/04/2023      _x86_64_        (4 CPU)


avg-cpu:  %user   %nice %system %iowait  %steal   %idle
           7,79    0,00    3,27    0,00    0,00   88,94

Device            r/s     rMB/s   rrqm/s  %rrqm r_await rareq-sz     w/s     wMB/s   wrqm/s  %wrqm w_await wareq-sz     d/s     dMB/s   drqm/s  %drqm d_await dareq-sz     f/s f_await  aqu-sz  %util
dm-0             0,00      0,00     0,00   0,00    0,00     0,00    7,80      0,04     0,00   0,00    0,21     5,03    0,00      0,00     0,00   0,00    0,00     0,00    0,00    0,00    0,00   0,36
dm-1             0,00      0,00     0,00   0,00    0,00     0,00    0,00      0,00     0,00   0,00    0,00     0,00    0,00      0,00     0,00   0,00    0,00     0,00    0,00    0,00    0,00   0,00
sda              0,00      0,00     0,00   0,00    0,00     0,00    0,00      0,00     0,00   0,00    0,00     0,00    0,00      0,00     0,00   0,00    0,00     0,00    0,00    0,00    0,00   0,00
sdb              0,00      0,00     0,00   0,00    0,00     0,00    4,10      0,04     3,70  47,44    1,41     9,37    0,00      0,00     0,00   0,00    0,00     0,00    0,40    2,75    0,01   0,36


Descrição das variáveis:
%util - porcentagem que o disco está servindo requisições. Valores muito altos indicam fila no disco.