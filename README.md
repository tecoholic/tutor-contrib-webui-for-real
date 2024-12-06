# webui-for-real plugin for [Tutor](https://docs.tutor.edly.io)

An actual web UI for Tutor.

> [!WARNING]
> This is a Proof Of Concept project at this stage. The upstream click-web library constructs it's own context for the Tutor CLI with the default `TUTOR_ROOT`.
> So, if you have your tutor directory set to some other directory, the UI won't be usable to accomplish anything meaningful. You can still browse the commands.

![Screenshot of the Web UI](screenshot.png)


## Installation

```sh
pip install git+https://github.com/tecoholic/tutor-contrib-webui-for-real
```

## Usage

```sh
tutor plugins enable webui-for-real
tutor webui-for-real start
```

The real webui should be accessible from http://localhost:5000.

## License

This software is licensed under the terms of the AGPLv3.
