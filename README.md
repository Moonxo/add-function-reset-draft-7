# add-function-reset-draft-7
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
