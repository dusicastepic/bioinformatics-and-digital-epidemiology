### Putative Disease Proteins Detection

In this section we used tool called DIAMOnD (https://github.com/barabasilab/DIAMOnD).

We just changed some commands in order to run it on python3. And as input we put files: seed.txt and all4.txt.
First one contains seed genes, second one contains PPI network. Results stored in first_200_added_nodes_weight_1.txt.

And then we used enrichr. There are results attached here.


labels = ['Official Symbol Interactor A','Official Symbol Interactor B','gene symbol']

biogrid[labels[0:2]].to_csv('all4.txt', header=False,index=False)

seedgene[labels[2]].to_csv('seed.txt', header=False,index=False)

for enrich
nodes = pd.read_csv("first_200_added_nodes_weight_1.txt", sep='\t')

nodes['DIAMOnD_node'].to_csv('list.txt',header=False,index=False)

