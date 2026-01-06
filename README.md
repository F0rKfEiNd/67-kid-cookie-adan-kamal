$session = New-Object Microsoft.PowerShell.Commands.WebRequestSession
$session.UserAgent = "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/143.0.0.0 Safari/537.36"
$session.Cookies.Add((New-Object System.Net.Cookie("cf_clearance", "9pn8RdM4QLe10yw18V.h0K.jVnIgCeOhAXa2_t3nLWI-1767703902-1.2.1.1-GIF5l2koiF.I9FIVHCH6cTsbYMrSZ1t5uYVJgsXvs__FT404bNMMLxFWslQIwANZrKmPMPsZ96O0yjst3rzGEQIza1F0lPvj03lGEYSLaOAe9NdYMnWWifj8VLFsOOfug1De6X_3wdEa9gxo5nFT8xT2_usx_3IZ2qFX3K5P4I92nqrOfYyjMweikMwhBKKM1Z9ONrJ0NLsYkS8hFVNJ7ArwymHhpjSXmINQgEfcRzQ", "/", ".clever.com")))
$session.Cookies.Add((New-Object System.Net.Cookie("_ga", "GA1.1.1206768176.1767703931", "/", ".clever.com")))
$session.Cookies.Add((New-Object System.Net.Cookie("clever-authenticator-production.sid", "s%3AbQDH3KjdC-k4Z3KDD9bJVtIqC9GlEJxMV.Wvomjgc9bSwKGv8F4rO4VZfBvCY8zCzY7hOZM8xJE%2Fg", "/", ".clever.com")))
$session.Cookies.Add((New-Object System.Net.Cookie("district", "s%3A511960e1f47e973a6500000e.bVJX5Oo8jgZ4gald6Hurf1OghyHAfM4XTNcDCXIEFlo", "/", "clever.com")))
$session.Cookies.Add((New-Object System.Net.Cookie("clever-portal.prod.session", "jIKFTH7IDYW6QgqstyAhQQ.Cz9iH5hjmPirzKkXtBUiEVpjhCLtDPMR-duAKtIj1CPiVtNvGD-b5f_AP6ZkNcPEvji64xj7mUb2MyXyXENeSoeEt8CYocwouCTkS9g18qcaBm3uJp-A3NahakOhGp-3qKqGSjRND46EODHVlRo6rj7T-gMLGHjHOxntf4zseBU3CKgXa-UzbFIwlnzvxpeWBHJHa8L4kHQG4t9LqU_boZjFC0MOLqDD2VlWqLqGbb6w0Iq65MRXDylKaTX7tOBqozbUkmI3cuwZLUiddNBm8K5jB7PdSRJ2QfJI7jMSkCOq5XIiDauZ2mcwDdHIGE23zOLiYJOuti6MaVBcj_XL3f0CWxKGErmRfjYLQ7xJRBA83zxlU7GHhi4gbE5NKVfK8_Qv75j6AFkMkE0m-5GIpw.1767703904581.86400000.QtuDWYnaUn1FJ593UUn0DbdcM6IDc2AioPp3GxIjWlQ", "/", ".clever.com")))
$session.Cookies.Add((New-Object System.Net.Cookie("_ga_RKDHZLJBH6", "GS2.1.s767703931`$o1`$g0`$t1767703934`$j57`$l0`$h0", "/", ".clever.com")))
Invoke-WebRequest -UseBasicParsing -Uri "https://clever.com/in/broward/student/portal" `
-WebSession $session `
-Headers @{
"authority"="clever.com"
  "method"="GET"
  "path"="/in/broward/student/portal"
  "scheme"="https"
  "accept"="text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7"
  "accept-encoding"="gzip, deflate, br, zstd"
  "accept-language"="en-US,en;q=0.9"
  "cache-control"="max-age=0"
  "priority"="u=0, i"
  "referer"="https://clever.com/"
  "sec-ch-ua"="`"Google Chrome`";v=`"143`", `"Chromium`";v=`"143`", `"Not A(Brand`";v=`"24`""
  "sec-ch-ua-mobile"="?0"
  "sec-ch-ua-platform"="`"Windows`""
  "sec-ch-ua-platform-version"="`"19.0.0`""
  "sec-fetch-dest"="document"
  "sec-fetch-mode"="navigate"
  "sec-fetch-site"="same-origin"
  "sec-fetch-user"="?1"
  "upgrade-insecure-requests"="1"
}
