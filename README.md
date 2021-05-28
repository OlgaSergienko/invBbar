# invBbar
A repository for comsol models that compute a steady-state ice-shelf profile for a given distribution of Bbar and invert for this distribution using solutions of the forward model as 'data'. 
To create the 'data' run the forward model ice_shelf_fwd5_5.mph and export H, u and v in Export section. To invert for Bbar, in ice_shelf_invBbar5_5.mph in Interpolation u_fwd, v_fwd and H_fwd provide the path to a .txt file exported from the forward model and run the model.
