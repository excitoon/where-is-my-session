# `wims`

Tool for extracting URLs from Firefox session files.

FYI: browser is a bad place to store your URLs.

## Usage

```
wims [--show-titles] [path]
```

## Example

```
wims recovery.jsonlz4
```

Or simply (Windows only):

```
wims
```

## Dependencies

```
pip3 install lz4
```

## See also

- https://github.com/andikleen/lz4json
- https://gist.github.com/Tblue/62ff47bef7f894e92ed5
- https://github.com/lilydjwg/mozlz4-tool

# `wims-edge`

Tool for extracting URLs from Edge session files.

FYI: this browser is worst place to store your URLs.

## Usage

```
wims-edge [--show-titles] [path]
```

## Example

```
wims-edge %UserProfile%\AppData\Local\Packages\Microsoft.MicrosoftEdge_8wekyb3d8bbwe\AC\MicrosoftEdge\User\Default\Recovery\Active
```

Or simply (Windows only):

```
wims-edge
```

## Dependencies

```
pip3 install olefile
```

## See also

- http://www.swiftforensics.com/2011/09/internet-explorer-recoverystore-aka.html
