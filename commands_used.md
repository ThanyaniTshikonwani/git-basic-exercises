4	 mkdir git-basic-exercises
5	 cd git
6	 cd git-basic-exercises/
7	 ls -a
8	 git init
9	 ls -a
10	 touch README.md
11	 ls -a
12	 git status
13	 git add .
14	 git status
15	 git commit -m "Initial commit"
16	 git log
17	 nano README.md 
18	 cat README.md 
19	 git status
20	 git add .
21	 git commit -m "Second commit"
22	 git log
23	 nano README.md 
24	 cat README.md 
25	 git status
26	 git add .
27	 git commit -m "Third commit"
28	 git log
29	 git checkout 1edae5d85f20479bbb2f21e6f892e18e71613994
30	 cat README.md 
31	 git checkout master
32	 cat README.md 
33	 git branch
34	 git branch milkshake-flavours
35	 git branch
36	 git checkout milkshake-flavours 
37	 nano milkshakes.md
38	 ls -a
39	 git branch
40	 git status
41	 git add .
42	 git commit -m "added initial flavours"
43	 git log
44	 git checkout master 
45	 git branch history
46	 git branch 
47	 history > history.txt
48	 git checkout history 
49	 cat history.txt 
50	 git status
51	 git add .
52	 git commit -m "added history"
53	 git log
54	 git checkout milkshake-flavours 
55	 git log
56	 ls -a
57	 nano README.md 
58	 git checkout history 
59	 cat README.md 
60	 rm README.md 
61	 echo "booya"> README.md
62	 git status
63	 git add .
64	 git commit -m "rewrote readme"
65	 git checkout master 
66	 cat README.md 
67	 ls
68	 git log
69	 git checkout milkshake-flavours 
70	 ls
71	 git log
72	 git checkout history 
73	 ls
74	 git log
75	 git checkout master 
76	 git merge milkshake-flavours 
77	 ls
78	 git log
79	 git merge history 
80	 ls
81	 git log
82	 git checkout history 
83	 git log
84	 git checkout milkshake-flavours 
85	 git log
86	 git remote add origin https://github.com/ThanyaniTshikonwani/git-basic-exercises.git
87	 git push -u origin master
88	 cd ../
89	 git clone https://github.com/Umuzi-org/tech-department.git
90	 ls
91	 cd tech-department/
92	 git branch
93	 git log
94	 git checkout project/git-basic-exercises
95	 git remote -v
96	 cd ..
97	 cd ../
98	 ls
99	 cd recruit/
100	 ls
101	 cd git-basic-exercises/
102	 git log
103	 ls -a
104	 cd 
105	 mkdir this-wil-be-another-repo
106	 cd this-wil-be-another-repo/
107	 git init
108	 touch README.md
109	 git status
110	 git add .
111	 git commit -m "Stage then Commit"
112	 cd
113	 ls
114	 cd git-basic-exercises/
115	 git log
116	 git branch
117	 git branch master 
118	 git checkout master 
119	 git push
120	 git checkout milkshake-flavours 
121	 git push
122	 git push -u origin master
123	 git push -u origin milkshake-flavours 
124	 git push -u origin history  
125	 git branch
126	 git checkout master 
127	 touch ingore-me.db
128	 git status
129	 nano .gitignore
130	 git status
131	 nano .gitignore
132	 git status
133	 mkdir large-directory-that-should-be-local-only
134	 cd large-directory-that-should-be-local-only/
135	 touch readme.md
136	 echo "this large thing should be the only one" > readme.md 
137	 cat readme.md 
138	 cd ..
139	 git status
140	 nano .gitignore 
141	 git status
142	 git add .
143	 git commit -m "Final Git Basic Commit"
144	 git status
145	 history
