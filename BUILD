genrule(
	name='x',
	outs=['x.txt'],
	cmd='sleep 5; echo hello > $@',
)

genrule(
	name='y',
	srcs=['x'],
	outs=['y.txt'],
	cmd='cp $(location x) $@',
)