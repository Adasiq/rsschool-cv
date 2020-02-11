# Anton Adasik

## Contacts
 - email: anthonyadasiq@gmail.com
 - telegram: @adasiq
 - mobile: +375447455334

## Summary
 I'd like to start a career of front-end developer

 ## Skills
 - git
 - JS basics, c++/c/arduino c basics, html, css

## Code examples
```
template <class T>
void solution(T **arr, int n, T k) {
	for (int i = 0; i < n; i++) {
		for (int j = 0; j < n; j++) {
			arr[i][j] = 0;
		}
	}
	for (int i = 0; i < n; i++) {
			for (int j = 0; j <= i; j++) {
				if (j <= n - i - 1) {
					arr[i][j] = (j+1)/k ;
				}
			}
	}
	int p;
	for (int i = 0; i < n; i++) {
		p = 1;
		for (int j = n - i - 1; j < n; j++) {
			if (j >= i) {
				arr[i][j]  =  (n - j) / k;
			}
		}
	}
	cout << "Array:" << endl;
	for (int i = 0; i < n; i++) {
		for (int j = 0; j < n; j++) {
			cout << setw(8) << arr[i][j]  ;
		}
		cout << endl;
	}
}


```

## Experience


## Education
 - BSU The Faculty of Radiophysics and Computer Science, 2 course
 - BelHard courses "Html/css/Js basics"

## Languages
  - i hope my english is on b1-b2 lvl
