# FIleDownloader-Class-to-Download-FIles-
This class is used to download files like pdf ,doc, xls etc

Source :- https://stackoverflow.com/a/56580009/10422074


** Here is how to call this class 

```swfit

let url = URL(string: "http://www.filedownloader.com/mydemofile.pdf")
FileDownloader.loadFileAsync(url: url!) { (path, error) in
    print("PDF File downloaded to : \(path!)")
}

```
