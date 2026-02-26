# Linux Basic Commands Notes (DevOps Preparation)
Check current shell
echo $SHELL
List files & directories
ls

Shows files and folders in current directory.

Change directory
cd /path

Example:

cd /tmp
Present working directory
pwd

Shows current location in filesystem.

Create directory
mkdir new_dir

Create multiple directories:

mkdir dir1 dir2 dir3

Create nested directory (parent + child together):

mkdir -p /tmp/asia/india/bangalore

-p → creates parent directories automatically.

Remove directory (recursive)
rm -r /tmp/my_dir

Deletes folder + all files inside.

Force delete:

rm -rf /tmp/my_dir

Deletes without asking confirmation.

Copy files
cp source destination

Example:

cp file1.txt /tmp/

Copy directory:

cp -r my_dir /tmp/my_dir
Move / Rename file

Rename:

mv oldname newname

Move file:

mv file1.txt /tmp/
Create empty file
touch new_file
Create file using cat
cat > new_file

Type content → press CTRL + D to save.

View file content
cat new_file
Edit file using vi editor
vi new_file

press i → insert mode

type text

press Esc

type :wq → save & exit
Delete file
rm new_file
Important Note

In Linux:

Deleting a file depends on directory write + execute permission, not the file permission.
