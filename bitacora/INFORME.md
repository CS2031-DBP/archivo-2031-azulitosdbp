| Hallazgo | Dónde estaba | Técnica de Git | Comando exacto | Referencia |
|---|---|---|---|---|
| FRAG-01 | Archivo borrado en la rama principal | Recuperar contenido de un commit anterior al borrado | `git show 881be66~1:bitacora/frag-01.txt` | `881be66` |
| FRAG-02 | Mensaje del tag anotado, respaldo previo al incidente | Leer mensaje completo de un tag | `git tag -n99 respaldo/pre-incidente` | `f9a9ce8` |
| Glifo del sello | Mismo commit del respaldo, archivo assets/sello.svg | Recuperar archivo desde una referencia (tag) | `git show f9a9ce8:assets/sello.svg` | `f9a9ce8` |
