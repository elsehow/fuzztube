# fuzztube

cli to get a high-quality audio file from a yoube video

## install

first, make sure you've installed [youtube-dl](https://github.com/rg3/youtube-dl). *this is required!*

you will also need ffmpg or avconv, and ffprobe or avprobe.

once you have those dependencies,

```
npm install -g fuzztube
```

## use

    fuzztuble [url]

fuzztube will print json to stdout

it will exit silently when done

(*if you see a random error*, check that the audio file has been downloaded.)

## licensed

BSD
