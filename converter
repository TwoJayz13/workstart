import json
from bencodepy import decode_from_file

def torrent_to_json(file_path):
    # Decode the torrent file
    decoded = decode_from_file(file_path)

    # Convert to json
    json_data = json.dumps(decoded)

    return json_data

file_path = 'path_to_your_torrent_file.torrent'
json_data = torrent_to_json(file_path)
print(json_data)
