Easy Step:
1- Download DynamicLightEditor.cs
2- Find the DynamicLightEditor in your Unity project: Assets\2DDL\2DLight\Core\Editor and delete it
3- Paste the DynamicLightEditor.cs you just downloaded from here

Other easy step:
1- Open the DynamicLightEditor.cs in your project file Assets\2DDL\2DLight\Core\Editor
2- Find line 847 and 848 
3- Replace them with: searchString = EditorGUILayout.TextField(searchString, EditorStyles.toolbarSearchField, GUILayout.Width(150));
if (GUILayout.Button("", EditorStyles.toolbarButton))

# 2D-Dynamic-Light-and-Shadows-fix-for-Unity-6
2D Dynamic Light and Shadows made by Apptouch fix for Unity newer version tested on Unity 6
for step by step tutorial watch this youtube video:
https://youtu.be/SH_okcuZlJY?si=vBx-WZOvYgoPHbtB

link for the original asset made by Apptouch:
https://assetstore.unity.com/packages/tools/particles-effects/2ddl-pro-2d-dynamic-lights-and-shadows-25933
