cat file1.txt file2.txt > combined.txt

cat combined.txt

mv combined.txt newfile.txt

touch file3.txt file4.txt

mkdir mydir

mv file3.txt file4.txt mydir/

rm -rf mydir file1.txt file2.txt newfile.txt

cp file1 file2

ln -s file1 file3

ln file1 file4

ls -i file1 file2 file3 file4

rm file1

mv file2 newfile2
mv file3 newfile3
mv file4 newfile4

ln -s newfile2 newlink

mkdir mydir2

mv newfile3 newfile4 newlink mydir2/
