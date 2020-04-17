# yawarakai-musicshare

Part of the Project Yawarakaijs

## Installation
This will add the component into yawarakai instance, you don't need any configuration for this component
```
$ yarn add @yawarakaijs/yawarakai-musicshare
```

## Development
Edit `config.json` file with the property `development` and set it to true   
Create a directory under yawarakai instance
```
$ mkdir Components && cd Components
```
Directly download this component as archived file and extract out
```
$ wget -L https://github.com/yawarakaijs/yawarakai-musicshare/archive/master.zip -O yawarakai-musicshare.zip
$ unzip yawarakai-musicshare.zip
```

## Available Commands
Netease CloudMusic keywords query
```
/netease (Under Construction)
```
Netease CloudMusic plylist info retrival
```
/playlist [text contains link format like music.163.com/playlist]
```
Netease CloudMusic album info retrival
```
/album [text contains link format like music.163.com/album]
```

## Available InlineQueries
Input text contains link format like `music.163.com/[playlist|song|album]`