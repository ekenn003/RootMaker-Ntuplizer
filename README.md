# RootMaker

Still missing: 
  - number of charged tracks in taus
  - puppi met / jets
  - unmatched gen particles

Recipe:

    # setup environment
    cmsrel CMSSW_8_0_12
    cd CMSSW_8_0_12/src
    cmsenv
    git cms-init
    
    # checkout and build
    git clone -b 80X https://github.com/ekenn003/RootMaker.git
    scramv1 b -j 20

# Danger! 
only keeps events with 3 or 4 leptons
