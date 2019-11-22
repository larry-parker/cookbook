Learned:
echo "Apple Pie" | git object-hash --stdin, creates hash of contents "Apple Pie"
echo "Apple Pie" | git object-hash --stdin -w , creates blob with contents "Apple Pie"

git cat-file <hash> -t, shows type
git cat-file <hash> -p, shows contents of hash

git count-objects , counts number of objects in object database
