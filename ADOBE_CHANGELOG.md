# About

We maintain a set of patches on top of upstream kube2iam. They need to be
semantically versioned as well so we understand, for example, that we're
upgrading a fix version of kube2iam vs a fix version of our patches.

The scheme followed has the upstream version then followed by our version:

```
K stands for upstream kube2iam version
A stands for Adobe's changes

{K major}.{K minor}.{K fix}-{A major}.{A minor}.{A fix}-adobe
```

# Changelog

