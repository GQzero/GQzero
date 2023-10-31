void Factorial() {
	int n;
	long long f = 1;
	cin >> n;
	for (int i = 1; i <= n; i++)
		f = f * i;
	cout << endl << f;
