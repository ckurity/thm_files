```
$ wget $ip/auditions/must_practice_corrupt_file.mp3
--2023-06-23 11:29:46--  http://$ip/auditions/must_practice_corrupt_file.mp3
Connecting to $ip:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1109983 (1.1M) [audio/mpeg]
Saving to: ‘must_practice_corrupt_file.mp3’

must_practice_corrupt_file.mp3    100%[==========================================================>]   1.06M   111KB/s    in 9.8s

2023-06-23 11:29:57 (111 KB/s) - ‘must_practice_corrupt_file.mp3’ saved [1109983/1109983]
```
```
$ ls -lh must_practice_corrupt_file.mp3
-rw-r--r-- 1 kali kali 1.1M May 19  2020 must_practice_corrupt_file.mp3
```
```
$ file must_practice_corrupt_file.mp3
must_practice_corrupt_file.mp3: Audio file with ID3 version 2.3.0, contains: MPEG ADTS, layer III, v1, 128 kbps, 44.1 kHz, JntStereo
```
```
$ md5sum must_practice_corrupt_file.mp3
134c0142a0ce9768a9c11edc39cf780e  must_practice_corrupt_file.mp3
```