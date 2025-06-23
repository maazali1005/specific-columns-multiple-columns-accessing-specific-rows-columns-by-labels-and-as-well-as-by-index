# select-a-columns-multiple-columns-accessing-specific-rows-columns-by-labels-and-as-well-as-by-index

print("Age---:\n",df[df['Age']>16])

print("City---:\n",df[df['City'].isin(['hyd','mum','ben'])])

print("multiple columns:\n",df[['Name','City']])

O/P:

Age---:

Name Age City

3 david 17 che

4 eve 18 mum

City---:

Name Age City

0 alice 14 hyd

1 bob 15 ben

4 eve 18 mum

multiple columns–:

Name City

0 alice hyd

1 bob ben

2 charlie kol

3 david che

4 eve mum
