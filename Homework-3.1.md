1 the function  local function checkPositiveNumber(value, name)
  if type(value) ~= 'number' or value <=0 then
    error(name .. " must be a positive number (was: " .. tostring(value) ..")")
  end
end


the variables    self.angle = angle
  self.cos, self.sin = math.cos(angle), math.sin(angle)
  
  
  
  math    local gameraMt = {__index = gamera}
local abs, min, max = math.abs, math.min, math.max