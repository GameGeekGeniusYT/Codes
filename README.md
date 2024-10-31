local plank = script.Parent

function Change()
	plank.BrickColor = BrickColor.Random()
end

while wait(1) do
	Change()
end
