#Comando iostat 

iostat -mxy 10 -o JSON
``

{"sysstat": {
        "hosts": [
                {
                        "nodename": "host",
                        "sysname": "Linux",
                        "release": "amd64",
                        "machine": "x86_64",
                        "number-of-cpus": 4,
                        "date": "33/04/2023",
                        "statistics": [

                                {
                                        "avg-cpu":  {"user": 8.68, "nice": 0.00, "system": 2.95, "iowait": 0.03, "steal": 0.00, "idle": 88.35},
                                        "disk": [
                                                {"disk_device": "dm-0", "r/s": 1.50, "w/s": 5.59, "d/s": 0.00, "f/s": 0.00, "rMB/s": 0.01, "wMB/s": 0.03, "dMB/s": 0.00, "rrqm/s": 0.00, "wrqm/s": 0.00, "drqm/s": 0.00, "rrqm": 0.00, "wrqm": 0.00, "drqm": 0.00, "r_await": 0.53, "w_await": 0.21, "d_await": 0.00, "f_await": 0.00, "rareq-sz": 6.13, "wareq-sz": 5.14, "dareq-sz": 0.00, "aqu-sz": 0.00, "util": 0.60},
                                                {"disk_device": "dm-1", "r/s": 0.00, "w/s": 0.00, "d/s": 0.00, "f/s": 0.00, "rMB/s": 0.00, "wMB/s": 0.00, "dMB/s": 0.00, "rrqm/s": 0.00, "wrqm/s": 0.00, "drqm/s": 0.00, "rrqm": 0.00, "wrqm": 0.00, "drqm": 0.00, "r_await": 0.00, "w_await": 0.00, "d_await": 0.00, "f_await": 0.00, "rareq-sz": 0.00, "wareq-sz": 0.00, "dareq-sz": 0.00, "aqu-sz": 0.00, "util": 0.00},
                                                {"disk_device": "sda", "r/s": 0.00, "w/s": 0.00, "d/s": 0.00, "f/s": 0.00, "rMB/s": 0.00, "wMB/s": 0.00, "dMB/s": 0.00, "rrqm/s": 0.00, "wrqm/s": 0.00, "drqm/s": 0.00, "rrqm": 0.00, "wrqm": 0.00, "drqm": 0.00, "r_await": 0.00, "w_await": 0.00, "d_await": 0.00, "f_await": 0.00, "rareq-sz": 0.00, "wareq-sz": 0.00, "dareq-sz": 0.00, "aqu-sz": 0.00, "util": 0.00},
                                                {"disk_device": "sdb", "r/s": 1.50, "w/s": 1.00, "d/s": 0.00, "f/s": 0.40, "rMB/s": 0.01, "wMB/s": 0.03, "dMB/s": 0.00, "rrqm/s": 0.00, "wrqm/s": 4.60, "drqm/s": 0.00, "rrqm": 0.00, "wrqm": 82.14, "drqm": 0.00, "r_await": 0.33, "w_await": 1.50, "d_await": 0.00, "f_await": 2.75, "rareq-sz": 6.13, "wareq-sz": 28.00, "dareq-sz": 0.00, "aqu-sz": 0.00, "util": 0.60}
                                        ]
                                }
                        ]
                }
        ]
}}

``

Descrição das variáveis:
%util - porcentagem que o disco está servindo requisições. Valores muito altos indicam fila no disco.

