This file is a patch of TransRec ([Code](https://drive.google.com/file/d/0B9Ck8jw-TZUEVmdROWZKTy1fcEE/view?usp=sharing)), published by the authors of "Translation-based Recommendation" (RecSys '17).

We are very grateful to the authors for publishing the code.

## How to create this patch

```sh
LANG=C diff -ruB --new-file /path/to/original/TransRec/sequential_rec/ /path/to/my/TransRec/sequential_rec/ > sequential_rec.patch
```

## What's new?

* Output the predicted items for a fixed user
* Convert gPlusPlaceId to a real place name
