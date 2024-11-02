![Tetra Core Cover Image](images/TetraCore.png)

# Dependency #

This package has a dependency on the other asset : [Tetra Attributes](https://assetstore.unity.com/packages/tools/utilities/tetra-attributes-256483) which is free. You **need** to download and **import** it in your project so you don't have any missing assembly reference when importing Tetra Core.

# Importing the Asset #
If you not familiar on how to install an asset, once you have purchased it, click on **Window → Package Manager** to reveal a window with all your available assets.

Type in the search field **Tetra Core** to download and install the last version. Follow the steps and wait till Unity finishes compiling your project.

# Introduction #

**TetraCore** is a collection of C# extension methods and utility scripts for Unity.

I've made this library to avoid writing the same block of code for every project, here is few examples :
- Checking whether a GameObject entering a collider trigger has the expected LayerMask.
- Trying to Add an element to a list if it's not already in it.
- Changing the transparency of an image's color.
- Showing/Hiding a CanvasGroup.
- Shuffling a list, get a random element from it.
- Destroying all children from a transform.

# Package structure #

```Assets
├─ Tetra Creations
│  ├─ Tetra Core
│  │  ├─ Examples
│  │  │  ├─ Audio Manager
│  │  │  ├─ Collections
│  │  │  ├─ Float Value Condition
│  │  │  ├─ Loading Assets
│  │  │  ├─ Scenes
│  │  │  ├─ Timer Manager
│  │  │  ├─ Vector3
│  │  ├─ Scripts
│  │  │  ├─ Runtime
│  │  │  │  ├─ Enums
│  │  │  │  ├─ Extensions
│  │  │  │  ├─ Utilities
│  │  │  ├─ Editor
│  │  ├─ Third Party Assets
```

- Audio Manager : Using TetraAttributes and TetraCore to simplify managing audio settings
- Collections : Extensions methods for ICollection and IList
- Float Value Condition : Trigger some code when a float reach a certain value.
- Loading Assets : Using AssetDatabaseExtensions to get all assets from a folder.
- Scenes : All examples scenes
- Vector3 : Move and scale an object along a path using Vector3 extensions.

> [!NOTE]
> There is a lot of extensions methods which I do not use in theses examples that you will have to explore.
