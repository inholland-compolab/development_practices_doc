How to comment
A comment within a script explains the purpose of several lines without explicitly stating the obvious. The next developer should be able to continue the work with support of the comments. A comment example is stated (using //) below on line 1:
'''c# 
1|  //Hide start menu and spawn inspection mode menu
2|  public void OpenInspectionMode() {
3|      start.SetActive(false);
4|      Instantiate(inspection);
5|  }
'''

C++ and C# use // (two-slashes) to comment a single line while Python uses # (hash sign). In case the comment spans multiple lines (block comments) in a row, both languages use the same comment syntax:
'''c# 
1|  /*Hide start menu and 
2|    spawn inspection mode 
3|    menu*/
4|  public void OpenInspectionMode() {
5|      start.SetActive(false);
6|      Instantiate(inspection);
7|  }
'''
 
An unclear comment example, states what already is written:
'''C#
1|  //Deactivate start menu and instantiate inspection menu
2|  public void OpenInspectionMode() {
3|      start.SetActive(false);
4|      Instantiate(inspection);
5|  }
''' 
