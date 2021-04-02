# Some tips for configuring spacemacs

## Source Code Pro Font
https://github.com/adobe-fonts/source-code-pro

## start maximized
set at `dotspacemacs/init`
`dotspacemacs-maximized-at-startup t`

## line numbers
set at `dotspacemacs/init`
`dotspacemacs-linenumbers t`

## python setup
add to `dotspacemacs-configuration-layers` .spacemacs 
```lisp
    python
    lsp
```

## configure for conda environments
add to `dotspacemacs-configuration-layers` .spacemacs 
```lisp
     conda
     (conda :variables conda-anaconda-home "/home/fox/miniconda3")
```

## activate environment
`conda-env-activate ( , n a )`

## lsp does not complete even if env is set
if sometimes LSP doesn't want to find a package try restarting it
`lsp-workspace-restart ( , b r )`
