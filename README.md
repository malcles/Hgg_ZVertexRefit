

Hgg_ZVertexRefit


- Code to reproduce the vertex collection without the muons tracks in Z events
- For Higgs to 2 photons vertex validation
- this versions works on 2017 Data in CMSSW_9_2_1 but can probably work in other releases

For regular users:

- install the code

cmsrel CMSSW_9_2_8

cd CMSSW_9_2_8/src

cmsenv

git cms-init

cd $CMSSW_BASE/src
  
git clone https://github.com/malcles/Hgg_ZVertexRefit Validation/Hgg_ZVertexRefit


- compile

scram b -j 3

- to run it:

cmsRun Validation/Hgg_ZVertexRefit/python/miniAOD-prod_PAT_DATA_AllVerticesCollFiltered.py

- or use crabAllData.py file and modify it accordingly to what you want to do
