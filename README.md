<img width="300" alt="GIF" align="right" src="https://github.com/ogjojo/ogjojo/blob/main/static/microsoftparty.gif">
@ogjojo

</br>
</br>
</br>
</br>

`profile.c`
```c
#include <stdio.h>

void name(){
	printf("NAME\n");
	char name[] = "Jesse";
	char alias[] = "ogjojo";
	printf("Name : %s\nAlias : %s\n\n", name, alias);
}

void skills(){
	printf("SKILLS\n");
	char code[] = "Python (intermediate), Javascript (intermediate), C (noob)";
	char languages[] = "Swedish, Finnish, English";
	printf("Programming : %s\nLanguages : %s\n\n", code, languages);
}

void links(){
	printf("LINKS\n");
	char website[] = "www.whereistayuplate.com";
	printf("Website : %s\n\n", website);
}

int main(void){
	name();
	skills();
	links();
	return 0;
}
```
