# Unexpected List Modification with removeIf()

This example demonstrates an uncommon Kotlin bug related to the `removeIf` function's in-place modification of lists.  The `removeIf` function modifies the list directly, which can lead to unexpected behavior if not handled carefully.  This is especially relevant when working with lists passed around in a program.