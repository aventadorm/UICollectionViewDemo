# UICollectionViewDemo
UICollectionView demo working on Xcode 7.
I personally faced issues getting this working, despite being a relatively simple thing to accomplish. After the Xcode 7 update, the [self.collectionView registerClass:[UICollectionViewCell class] forCellWithReuseIdentifier:reuseIdentifier] line added automatically by Xcode 7 creates the problem. This line should be commented out to make the collectionview work. Nevertheless, uploaded this here for my own future reference and for others to have a readymade working template.
