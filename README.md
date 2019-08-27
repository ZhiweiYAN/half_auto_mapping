# half_auto_mapping

The codes read these Chinese keywords embraced with double braces first,
and search them inside a mapping table with MS excel format in order to
find the corresponding English phrase. Then, according to the English
phrases, it find the json keywords in a json file. Finally, It joins the
multiple keywords along the json tree and the joined English phrases are
put back into the original latex file in place of those Chinese keywords.
