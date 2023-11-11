import configuration
import requests
import data



def post_new_order(): # запрос на создание заказа
    return requests.post(configuration.URL_SERVICE + configuration.CREATE_NEW_ORDER,  # подставить URL
                         json=data.order_body)  # тело



def get_orders_track(track_id): # запрос получения заказа по его трекингу
    return requests.get(configuration.URL_SERVICE + configuration.RECEIVING_ORDER_BY_ID + "?t=" + str(track_id))
