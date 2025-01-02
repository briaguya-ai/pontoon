# pontoon

flatpak stuff

```
flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install builddir org.harbourmasters.soh.yml
flatpak run org.harbourmasters.soh
flatpak remove org.harbourmasters.soh
```
