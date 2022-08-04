# grafos-exemplos
public class Estado_BFS : Estado_Base
02. {
03. public const int e_0 = 0;
04. public const int e_1 = 1;
05. public const int e_2 = 2;
06. [...]
07. public static Estado_BFS Estado_BFS_0 = new Estado_BFS(e_0);
08. public static Estado_BFS Estado_BFS_1 = new Estado_BFS(e_1);
09. public static Estado_BFS Estado_BFS_2 = new Estado_BFS(e_2);
10. [...]
11. private Estado_BFS(int valor)
12. : base(valor) { }
13. }
