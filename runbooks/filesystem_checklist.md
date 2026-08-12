To check if a disk is full or not i do --> df -h
and to check about the indoes i do --> df -i

If a file is delted and to check if it being held and used by some process or not --> sudo lsof | grep deleted

Memfree is the ram space being used for cache in the free time to speed up the data retirevel from disk process , i always shows low because that free spaceis being counted as used in Memfree, but in the case of MemAvailable it doesn't count that cache space as used but rather add it in the recliamable space which can be considered free and can be used 
