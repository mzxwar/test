function()
    return C_NamePlate.GetNamePlateForUnit('target')
end



function()
    if aura_env.state and aura_env.state.unit then
        return C_NamePlate.GetNamePlateForUnit(aura_env.state.unit)
    end
end
