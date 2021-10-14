# kssmagister.github.io

## web page published with org-publish
Config:

```
 (setq org-html-validation-link nil            ;; Don't show validation link
        org-html-head-include-scripts nil       ;; Use our own scripts
        org-html-head-include-default-style nil ;; Use our own styles
        org-html-head "<link rel=\"stylesheet\" href=\"https://cdn.simplecss.org/simple.min.css\" />")



  (setq org-publish-project-alist
        '(("my-org-publish"
           :recursive t
           :base-directory "..."
           :publishing-function org-html-publish-to-html
           :publishing-directory "..."
           :section-numbers nil
           :with-creator t
           :time-stamp-file nil
           :auto-sitemap t
           :sitemap-filename "sitemap.org"
           :with-toc t)))
```
