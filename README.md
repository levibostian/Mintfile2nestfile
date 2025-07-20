# Mintfile2nestfile

Convert a https://github.com/yonaskolb/Mint config file into a https://github.com/mtj0928/nest config file. 

# Usage

From the directory containing your `Mintfile`:

```
curl -fsSL https://github.com/levibostian/Mintfile2nestfile/blob/HEAD/mintfile2nestfile.sh?raw=true | bash
```

# Why? 

Nest is faster than Mint but Mint has built-in Renovate Bot support. So, you can use this script to have your project contain a `Mintfile` for Renovate Bot to update, and then use this script to convert it to a `nestfile.yaml` to run nest using the Mint dependencies.