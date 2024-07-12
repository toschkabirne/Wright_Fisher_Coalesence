The code includes a lot of different tests for the created functions. If you just want to play around with the WF_model and create WF or coalescence sample trees, you just need the functions:
wrightfisher_model(N,t); wrightfisher_mrca(n,model,maxiter=50,test=False); expo_samples(n,N,toggle = True,m=1000) and for visualization:
draw_graph(G,xaxis=10,yaxis=12,title="Wright Fisher Genealogy"); graph_back_gen_wf(model); graph_sample_back_gen_wf(mrca,model); graph_coalescence_new_version(sampletimes):
The codes purpose is to visualize results from my Bachelor Thesis.
