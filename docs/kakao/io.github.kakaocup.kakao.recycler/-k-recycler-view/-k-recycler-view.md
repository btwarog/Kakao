//[kakao](../../../index.md)/[io.github.kakaocup.kakao.recycler](../index.md)/[KRecyclerView](index.md)/[KRecyclerView](-k-recycler-view.md)



# KRecyclerView  
[androidJvm]  
Content  
fun [KRecyclerView](-k-recycler-view.md)(builder: [ViewBuilder](../../io.github.kakaocup.kakao.common.builders/-view-builder/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), itemTypeBuilder: [KRecyclerItemTypeBuilder](../-k-recycler-item-type-builder/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  
More info  


Constructs view class with view interaction from given ViewBuilder



## See also  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>[io.github.kakaocup.kakao.common.builders.ViewBuilder](../../io.github.kakaocup.kakao.common.builders/-view-builder/index.md)| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>|
  


## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>builder| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a><br><br>ViewBuilder which will result in view's interaction<br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>itemTypeBuilder| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a><br><br>Lambda with receiver where you pass your item providers<br><br>|
  
  


[androidJvm]  
Content  
fun [KRecyclerView](-k-recycler-view.md)(parent: Matcher<[View](https://developer.android.com/reference/kotlin/android/view/View.html)>, builder: [ViewBuilder](../../io.github.kakaocup.kakao.common.builders/-view-builder/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), itemTypeBuilder: [KRecyclerItemTypeBuilder](../-k-recycler-item-type-builder/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  
More info  


Constructs view class with parent and view interaction from given ViewBuilder



## See also  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#org.hamcrest.Matcher[android.view.View]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>[io.github.kakaocup.kakao.common.builders.ViewBuilder](../../io.github.kakaocup.kakao.common.builders/-view-builder/index.md)| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#org.hamcrest.Matcher[android.view.View]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>|
  


## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#org.hamcrest.Matcher[android.view.View]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>parent| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#org.hamcrest.Matcher[android.view.View]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a><br><br>Matcher that will be used as parent in isDescendantOfA() matcher<br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#org.hamcrest.Matcher[android.view.View]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>builder| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#org.hamcrest.Matcher[android.view.View]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a><br><br>ViewBuilder which will result in view's interaction<br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#org.hamcrest.Matcher[android.view.View]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>itemTypeBuilder| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#org.hamcrest.Matcher[android.view.View]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a><br><br>Lambda with receiver where you pass your item providers<br><br>|
  
  


[androidJvm]  
Content  
fun [KRecyclerView](-k-recycler-view.md)(parent: DataInteraction, builder: [ViewBuilder](../../io.github.kakaocup.kakao.common.builders/-view-builder/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), itemTypeBuilder: [KRecyclerItemTypeBuilder](../-k-recycler-item-type-builder/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  
More info  


Constructs view class with parent and view interaction from given ViewBuilder



## See also  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#androidx.test.espresso.DataInteraction#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>[io.github.kakaocup.kakao.common.builders.ViewBuilder](../../io.github.kakaocup.kakao.common.builders/-view-builder/index.md)| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#androidx.test.espresso.DataInteraction#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>|
  


## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#androidx.test.espresso.DataInteraction#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>parent| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#androidx.test.espresso.DataInteraction#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a><br><br>DataInteraction that will be used as parent to ViewBuilder<br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#androidx.test.espresso.DataInteraction#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>builder| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#androidx.test.espresso.DataInteraction#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a><br><br>ViewBuilder which will result in view's interaction<br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#androidx.test.espresso.DataInteraction#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a>itemTypeBuilder| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView/KRecyclerView/#androidx.test.espresso.DataInteraction#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]#kotlin.Function1[io.github.kakaocup.kakao.recycler.KRecyclerItemTypeBuilder,kotlin.Unit]/PointingToDeclaration/"></a><br><br>Lambda with receiver where you pass your item providers<br><br>|
  
  


