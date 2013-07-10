# shellstream
> Version 0.4.0

# What

Shellstream is a simple python client that pipes your terminal IO to the web:

# installing

## pip makes it easy

    pip install shellstream

# running

To run StreamShell, you will need to receive an API Token from ___.  Just sign up and go to this page ___.

Add this token to your `.bash_profile`:

```python
STREAM_SHELL_TOKEN = [your token]
```

# limitations

## This initial version is naive.  It is not cross-platform at this point, depending on a number of unix commands. That will come with time.

# Motivation

When you've got an issue at the command line and need help online, copy and pasting your session on an ongoing basis is a pain.  Hence, I created shellstream along with the companion website.
