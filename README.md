itemId = 627 -- replace what u want to be dropped
while true do
  if getInventory():getItemCount(itemId) >= 1 then
      getBot():drop(itemId, 200)
  end
sleep(5000)
end
